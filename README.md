# Investment---Intrinsic-Value

Overview
This Python script provides two methodologies for calculating the intrinsic value of a stock: the Discounted Cash Flow (DCF) method and the Book Value Growth (BVG) method. Both approaches offer distinct perspectives on valuing a company, allowing investors to make more informed decisions based on their preferences and data availability.


## Discounted Cash Flow (DCF) Method

The DCF method estimates intrinsic value by projecting future cash flows and discounting them to present value. The script utilizes the Alpha Vantage API to fetch relevant financial data and calculates intrinsic value based on:

Current Free Cash Flow per Share

Free Cash Flow Growth Rate

Projected Number of Years

Weighted Average Cost of Capital (WACC)

Perpetual Growth Rate



## Book Value Growth (BVG) Method

The BVG method estimates intrinsic value by projecting the company's book value growth. The script fetches company overview and balance sheet data and calculates intrinsic value based on:

Current Book Value per Share

Book Value Growth Rate

Number of Years to Project

Ten-Year Treasury Rate

## Comparison
Both methods offer valuable insights into a company's intrinsic value, yet they differ in their core assumptions and applications.


### DCF Method:

Cash Flow Focus: DCF method considers future cash flows, which is particularly useful for companies with unpredictable earnings.

Dynamic Approach: Takes into account the time value of money, providing a more dynamic valuation.

Complexity: Requires more data inputs, including WACC and perpetual growth rate, which might be challenging for certain companies or industries.

### BVG Method:

Simplicity: BVG method is simpler, relying on historical book value trends and projecting forward.

Stability: Suitable for companies with stable book value growth, providing a more straightforward valuation for certain industries.

Assumptions: Assumes that book value growth is a reliable indicator of future value, which may not hold true for all companies.

Note
This script serves as a demonstration, and users are encouraged to adapt and customize it based on specific requirements or preferences. It's recommended to thoroughly understand both methodologies and consider factors such as the company's financial structure and industry when choosing an intrinsic value calculation method.

References
Alpha Vantage API
yfinance Documentation
Discounted Cash Flow (DCF) Method
Feel free to explore, compare, and adapt the script to suit your investment analysis needs!
