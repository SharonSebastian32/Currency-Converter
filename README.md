 
# Currency Converter Application

This project is a **Currency Converter** web application built using **React.js**. It allows users to convert an amount from one currency to another using live exchange rates. The app features a clean and responsive design, offering a smooth user experience for converting currencies on the go.

## Features

- **Real-Time Currency Conversion**: Fetches live exchange rates and calculates the conversion amount based on user input.
- **Swap Functionality**: Quickly swap between the selected currencies with a single click.
- **Responsive Design**: The application is fully responsive and adapts seamlessly across various screen sizes.
- **Custom Background**: The app features a stylish background image that enhances its overall aesthetic.

## Demo

![App Preview](src/assets/image.png)

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used

- **React.js**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for styling the application.
- **Custom Hooks**: Utilized to fetch and manage currency data.
- **JavaScript (ES6+)**: The core programming language used to develop the application.
- **OpenAPI** : (#https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/inr.json)

## Getting Started

Follow the steps below to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following installed on your machine:
- **Node.js** (v14 or higher)
- **npm** (Node Package Manager) or **yarn**

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/currency-converter-app.git
   cd currency-converter-app
   ```

2. **Install dependencies**:

   Using npm:

   ```bash
   npm install
   ```

   Or using yarn:

   ```bash
   yarn install
   ```

3. **Run the development server**:

   Using npm:

   ```bash
   npm start
   ```

   Or using yarn:

   ```bash
   yarn start
   ```

4. **View the application**:

   Open your browser and visit `http://localhost:3000` to interact with the application.

## Usage

1. **Select Currencies**: Choose the currencies you wish to convert from and to using the dropdown menus.
2. **Enter Amount**: Input the amount you wish to convert.
3. **Convert**: Click the **Convert** button to perform the currency conversion.
4. **Swap Currencies**: Click the **Swap** button to quickly exchange the selected currencies and perform a new conversion.

## Folder Structure

The basic structure of the project is as follows:

```
currency-converter-app/
│
├── public/
│   ├── index.html
│   └── ...
│
├── src/
│   ├── assets/              # Images and static assets
│   ├── components/          # Reusable UI components (e.g., InputBox)
│   ├── hooks/               # Custom hooks (e.g., useCurrencyHook)
│   ├── App.js               # Main application component
│   ├── index.js             # Entry point of the application
│   ├── styles/              # Global styles and Tailwind configuration
│   └── ...
│
├── package.json             # Project dependencies and scripts
├── README.md                # Project documentation
└── ...
```

## Contributing

Contributions are welcome! If you have any suggestions, issues, or improvements, please feel free to create an issue or submit a pull request.

### Steps to Contribute:

1. Fork this repository.
2. Create your feature branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m 'Add your feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
 
