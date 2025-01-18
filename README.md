# Currency Converter App 💱

A **React Native** application to convert Indian Rupee (INR) into multiple currencies in real-time. This app is built with simplicity and efficiency in mind, providing an intuitive interface and accurate conversions.  

## ✨ Features
- Convert INR to multiple currencies.
- Clean and user-friendly UI.
- Snackbar notifications for input errors.
- FlatList integration for rendering currency options.
- Displays conversion results with proper formatting.
- Dynamic button highlights for selected currency.

## 🚀 How It Works
1. Enter the amount in Indian Rupees (INR).
2. Select the target currency from the available options.
3. View the converted value displayed below the input field.

## 🛠️ Tech Stack
- **React Native**: For building the mobile application.
- **React Hooks**: For managing state (`useState`).
- **Snackbar**: For error and status notifications.
- **FlatList**: For rendering currency buttons in a grid layout.

## 📂 Project Structure
```
📦 CurrencyConverterApp
├── 📂 components
│   └── CurrencyButton.js  # Button component for currencies
├── 📂 constants
│   └── currencyByRupee.js # Currency conversion data
├── App.js                 # Main app logic and UI
└── package.json           # Project dependencies
```

## 🔧 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/currency-converter-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd currency-converter-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Run the app:
   ```bash
   npx react-native run-android
   # or for iOS
   npx react-native run-ios
   ```
   
## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to enhance the functionality or UI of this project.
