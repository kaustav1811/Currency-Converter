# 💱 Currency Converter

A responsive and interactive currency converter web application built using **HTML**, **CSS**, **JavaScript**, and the **Fetch API**. It allows users to convert values between currencies in real-time using live exchange rates and also displays country flags for selected currencies.

---

## 🌐 Features

- 🔁 **Live Currency Conversion**  
  Converts values from one currency to another using real-time exchange rates via an external API.

- 📥 **Dropdown Selection for Currencies**  
  Users can select both "From" and "To" currencies from fully populated dropdown lists.

- 🌍 **Automatic Flag Display**  
  Displays the national flag of the selected currency using [FlagsAPI](https://flagsapi.com).

- 🔃 **Default Currency Selection**  
  USD is set as the default "From" currency, and INR as the default "To" currency.

- 🔄 **Auto-Fetch on Page Load**  
  Automatically fetches the conversion rate and displays it when the page is loaded.

- ✋ **Form Validation**  
  Ensures the entered amount is a valid number (defaults to 1 if invalid).

---

## 🛠️ Technologies Used

- **HTML** – for the structure of the web page  
- **CSS** – for styling and layout  
- **JavaScript** – for all the interactive behavior and logic  
- **Fetch API** – to get live exchange rate data from the internet  
- **[@fawazahmed0/currency-api](https://github.com/fawazahmed0/currency-api)** – open-source exchange rates API  
- **[FlagsAPI](https://flagsapi.com/)** – to display country flags based on currency codes

---

## 📁 File Structure

- `index.html` – Main HTML file (not uploaded but assumed)  
- `style.css` – Styling file (not uploaded but assumed)  
- `currency_converter.js` – Main JavaScript logic for conversion and flag updates  
- `codes.js` – Contains mapping of currency codes to country codes for flag rendering

---

📌 To-Do Ideas (for future updates)
- Dark mode toggle
- Swap currencies button
- Add reset button
- Error handling for fetch failures
- Display historical exchange rate graph
- Currency symbol display (₹, $, €, etc.)
