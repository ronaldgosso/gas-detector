# 🔥 GasGuard Monitor (Gas Detector Dashboard)

Welcome to the **GasGuard Monitor**, a real-time interactive dashboard for visualizing sensor data, tracking gas leak incidents, and managing system settings.

---

## 🔗 Core Infrastructure & API Links

This dashboard is designed to consume data from the GasGuard API. To explore the backend infrastructure or view the live data feeds, please refer to the following links:

- 🐙 **API Repository source code:** [github.com/ronaldgosso/gas-detector-api](https://github.com/ronaldgosso/gas-detector-api)
- 🌐 **Live API Server:** [gas-detector-api.vercel.app](https://gas-detector-api.vercel.app)

---

## 🛠️ Developer Setup & Instructions

<details>
<summary><strong>Click here to expand Setup Instructions</strong></summary>

### Prerequisites
- Any modern web browser (Google Chrome, Firefox, Safari, Edge)
- No Node.js or backend requirement for the frontend alone

### Running the Application Locally
1. **Clone the repository:**
   ```bash
   git clone https://github.com/ronaldgosso/gas-detector.git
   ```
   *(Alternatively, you can fork the repository and clone your fork)*

2. **Navigate to the directory:**
   ```bash
   cd gas-detector
   ```

3. **Launch the Dashboard:**
   Simply open the `index.html` file in your preferred web browser.

### API Configuration
To ensure real-time data flows properly into your local instance:
1. Navigate to the **Settings** section within the dashboard.
2. Ensure the **API Endpoint** matches the hosted backend:
   ```text
   https://gas-detector-api.vercel.app
   ```
3. Click **Save Settings** to apply the changes.

</details>

## 🌟 Interactive Features

<details>
<summary><strong>Discover what GasGuard does (Click to Expand)</strong></summary>

- 📊 **Real-time Gas Level Monitor:** Dynamic charting using `Chart.js` to observe gas levels as they fluctuate.
- 📋 **Recent Incidents Logs:** Track previously recorded incident states, complete with JSON/CSV/PDF exporting options.
- 🎨 **Dynamic Theming:** Seamless switching between Light and Dark mode using a custom CSS variable implementation.
- 🚨 **Emergency Contacts & SMS:** Dedicated management block to configure contacts sent notifications if gas levels exceed standard thresholds (e.g. >800 PPM).

</details>

## 🤝 Contributing

Contributions to improve GasGuard Monitor are always welcome! Feel free to:
- **Fork** the repository
- **Create** a feature branch
- **Submit** a pull request

</details>
