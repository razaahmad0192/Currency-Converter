💱 Currency Converter

A simple and responsive Currency Converter built using React.js, which allows users to convert between different world currencies using live exchange rates.

🚀 Features

🔄 Real-time currency conversion

🌍 Supports multiple world currencies

📱 Fully responsive design (works on desktop & mobile)

⚡ Fast and smooth user interface using React hooks and state

🔢 Automatic rate fetching from exchange rate API

💾 Remembers last selected currencies (optional if you implemented localStorage)

🛠️ Technologies Used

React.js – Frontend framework

Axios / Fetch API – For fetching live exchange rates

CSS / TailwindCSS / Bootstrap – For styling (mention the one you used)

ExchangeRate-API / Frankfurter / FreeCurrencyAPI – For currency data (mention whichever you used)

🧩 Project Structure
Currency-Converter/
│
├── public/
│   └── index.html
│
├── src/
│   ├── components/
│   │   └── Converter.js
│   ├── App.js
│   ├── index.js
│   ├── App.css
│   └── api.js (if used)
│
├── package.json
└── README.md

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/yourusername/currency-converter.git
cd currency-converter


Install dependencies

npm install


Run the project

npm start


Build for production

npm run build

🔧 Usage

Select the base currency and target currency.

Enter the amount you want to convert.

Click Convert, and the app will show the converted value instantly.

🖼️ Screenshot

(Add a screenshot of your project UI here)

![App Screenshot](screenshot.png)

📡 API Reference

Example if you used ExchangeRate API
:

https://v6.exchangerate-api.com/v6/YOUR_API_KEY/latest/USD

🧠 Future Improvements

Add historical exchange rate graph

Add dark mode

Allow offline usage with cached rates

Add currency flags and country names

🧑‍💻 Author

Ahmed Raza

GitHub: @yourusername

LinkedIn: [your-linkedin-profile]

📄 License

This project is licensed under the MIT License – feel free to use and modify it.
