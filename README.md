


# FinVest

FinVest is a comprehensive platform designed to predict stock prices on the Bombay Stock Exchange (BSE) using advanced Machine Learning models. The platform analyzes patterns and market manipulations over the last 40 years, helping users make informed investment decisions. Additionally, it features **Arya**, an AI assistant that provides real-time insights and suggestions on the latest trends in the Indian stock exchange.

## Features

- **Stock Price Prediction**: Predict future trends in BSE using historical data and an advanced ML model.
- **AI Assistant - Arya**: Get real-time recommendations on stock trends in the Indian stock market.
- **Comprehensive Market Analysis**: Detect historical patterns and manipulations over the last four decades.

## Installation

To set up the project locally, follow the instructions below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/finvest.git
   cd finvest
   ```

2. **Create and activate a virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**:
   Create a `.env` file and add your API keys or other necessary environment variables as required by the project.

## Dependencies

The following Python packages are required for the project. These can be installed using the `requirements.txt` file.

- **annotated-types==0.6.0**
- **anyio==4.3.0**
- **attrs==23.2.0**
- **beautifulsoup4==4.12.3**
- **cachetools==5.3.3**
- **certifi==2024.2.2**
- **cryptography==41.0.7**
- **fastapi==0.110.1**
- **Flask==3.0.2**
- **google-api-python-client==2.126.0**
- **matplotlib==3.8.4**
- **numpy==1.26.4**
- **openai==1.16.2**
- **pandas==2.2.2**
- **requests==2.31.0**
- **scipy==1.13.0**
- **uvicorn==0.29.0**
- and many more listed in the `requirements.txt`.

## Usage

1. **Run the application**:
   To start the web server, use the following command:
   ```bash
   uvicorn main:app --reload
   ```
   Or, if using Flask:
   ```bash
   flask run
   ```

2. **Access the platform**:
   Open your browser and navigate to:
   ```
   http://127.0.0.1:8000  # or the appropriate URL for Flask
   ```

## How It Works

- **ML Model**: The core of FinVest is a Machine Learning model that uses historical stock data to predict future stock prices. It analyzes various features, including price movements, trading volumes, and historical patterns, to forecast trends.
  
- **Arya AI Assistant**: Arya provides users with insights based on the latest stock trends in the Indian stock market. The assistant helps users by suggesting potential opportunities based on market data and predictive analysis.

## Contributing

We welcome contributions! Please submit a pull request or open an issue for any bugs or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Contact

For any inquiries, please contact the project maintainers at:
- **Email**: shrey.mishra.dev@gmail.com
```

This `README` file contains sections for installation, usage, dependencies, features, and contribution details tailored for the FinVest project. You can modify it based on the specific repository and project structure.
