# Real-Time Currency Converter

A simple and intuitive web application that allows users to convert currency amounts between different countries in real-time. This project leverages the ExchangeRate-API to fetch the latest exchange rates and provides a clean, user-friendly interface for seamless currency conversion.

### ✨ Features

-   **Real-Time Exchange Rates**: Fetches up-to-date currency conversion rates from a live API.
-   **150+ Currencies**: Supports a wide range of global currencies to choose from.
-   **Dynamic Flag Icons**: Displays the national flag for each selected currency for better user experience.
-   **Swap Functionality**: Easily swap the "From" and "To" currencies with a single click.
-   **User-Friendly Interface**: A clean, simple, and responsive design built with HTML and CSS.
-   **Dynamic Updates**: The conversion result is automatically updated when the amount or currency is changed.

### 🛠️ Technologies Used

-   **Frontend**: HTML5, CSS3, Vanilla JavaScript
-   **API**: [ExchangeRate-API](https://www.exchangerate-api.com/) for real-time currency data.
-   **Icons**: Font Awesome for interface icons.

### 🚀 How to Run Locally

To run this project on your local machine, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/currency-converter.git](https://github.com/your-username/currency-converter.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd currency-converter
    ```

3.  **Get a free API Key:**
    -   Go to [ExchangeRate-API](https://www.exchangerate-api.com/) and sign up for a free API key.

4.  **Add your API Key:**
    -   Open the `script.js` file.
    -   On line 41, replace `'YOUR-API-KEY'` with the actual API key you received.
    ```javascript
    let url = `https://v6.exchangerate-api.com/v6/YOUR-API-KEY/latest/${fromCurrency.value}`;
    ```

5.  **Open in browser:**
    -   Open the `index.html` file in your web browser to use the application.

### 📝 How It Works

The application fetches the latest conversion rates for a selected base currency from the ExchangeRate-API. When a user enters an amount and selects two currencies, the JavaScript code calculates the converted amount using the fetched data and dynamically updates the DOM to display the result to the user. The flag icons are updated by mapping the currency code to a country code.

---

_This project was created as a personal project to practice working with APIs and DOM manipulation using Vanilla JavaScript._
