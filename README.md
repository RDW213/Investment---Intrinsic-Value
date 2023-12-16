# Investment---Intrinsic-Value

Overview
This Python script provides two methodologies for calculating the intrinsic value of a stock: the Discounted Cash Flow (DCF) method and the Book Value Growth (BVG) method. Both approaches offer distinct perspectives on valuing a company, allowing investors to make more informed decisions based on their preferences and data availability.

Discounted Cash Flow (DCF) Method
Methodology
The DCF method estimates intrinsic value by projecting future cash flows and discounting them to present value. The script utilizes the Alpha Vantage API to fetch relevant financial data and calculates intrinsic value based on:

Current Free Cash Flow per Share
Free Cash Flow Growth Rate
Projected Number of Years
Weighted Average Cost of Capital (WACC)
Perpetual Growth Rate
Usage
Replace the placeholder YOUR_API_KEY with your actual Alpha Vantage API key.
Define the stock symbol you want to analyze using the ticker variable.
Run the script.
Dependencies
pandas
numpy
yfinance
requests
Book Value Growth (BVG) Method
Methodology
The BVG method estimates intrinsic value by projecting the company's book value growth. The script fetches company overview and balance sheet data and calculates intrinsic value based on:

Current Book Value per Share
Book Value Growth Rate
Number of Years to Project
Ten-Year Treasury Rate
Usage
Replace the placeholder YOUR_API_KEY with your actual Alpha Vantage API key.
Define the stock symbol you want to analyze using the ticker variable.
Run the script.
Dependencies
pandas
numpy
yfinance
requests
Comparison
Both methods offer valuable insights into a company's intrinsic value. The DCF method focuses on cash flows, considering factors like WACC and perpetual growth, while the BVG method leverages the growth rate of the book value. Investors can choose the method that aligns with their investment philosophy and the nature of the business being analyzed.

Note
This script serves as a demonstration, and users are encouraged to adapt and customize it based on specific requirements or preferences. It's recommended to thoroughly understand both methodologies and consider factors such as the company's financial structure and industry when choosing an intrinsic value calculation method.

References
Alpha Vantage API
yfinance Documentation
Discounted Cash Flow (DCF) Method
Feel free to explore, compare, and adapt the script to suit your investment analysis needs!
