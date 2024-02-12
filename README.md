#  Project 1 - Group 4

## Introduction

This project brings to life an analytical platform designed to deliver in-depth insights into the fluctuations of currency exchange rates, emphasising the analysis of currency strengths, historical patterns, and the repercussions of significant financial downturns on currency valuations. Tailored for those engaged in forex trading, economic studies, or seeking knowledge about financial markets, this tool offers the advantage of real-time data visualisation coupled with retrospective analyses.

The goal of this project is twofold: it not only provides a reliable resource for monitoring and dissecting currency exchange rates but also sheds light on the mechanisms governing the currency markets under both standard and crisis conditions. This multifaceted utility renders the tool indispensable to a diverse audience, including forex market participants, students of economics, and finance aficionados, thereby enriching their understanding and engagement with the financial world.

 **Analysis questions:**
 1. Impact Analysis on Exchange Rates:
	 - Objective: To assess how AUD was affected during a specific historical event, in this case, the 2008 financial crisis.
2. How did AUD exchange rates change perform in 2023?
	- Objective: To track the historical performance of major currency pair, AUD/USD, and understand how their exchange rates have evolved over a specific time frame, in this case January - December 2023.
3. What are the current strong and weak currencies relative to a base currency?:
	 - Objective: To determine which currencies are currently performing well (strong) or poorly (weak) when compared to a specific base currency (in this case, the Australian Dollar, AUD).

**Group Members:**
1. Kai Huang
2. Oliver James Uy
3. Steph Adey

## Analysis Results

**Exchange Rate Changes in 2008:**

-   There were 8 currencies with a positive percentage change and 14 currencies with a negative percentage change when AUD was the base currency.
![enter image description here](https://github.com/Stephadey/Images/blob/main/Image-1-new.png?raw=true)
**Top Performer and Worst Performer:**

-   The AUD-GBP currency pair was the top performer indicating stregth in the AUD against this currency during this period.
-   The AUD-JPY currency pair was the worst performer indicating weakness in the AUD against this currency during this period.
![enter image description here](https://github.com/Stephadey/Images/blob/main/Image-2-new.png?raw=true)
**Major Currencies in the Worst Performers:**

-   JPY, CHF and USD were the Major currencies in the top 5 worst performers, indicating challenges against 3 major currencies during 2008 period.

**Performance of the Australian Dollar in 2023:**
![enter image description here](https://github.com/Stephadey/Images/blob/main/Image-3.png?raw=true)
-   The Australian dollar faced a challenging year in 2023 when measured against the USD, which is among the world's top ten strongest currencies. By September 2023, it had reached a low point of 63.58 US cents, marking its lowest level in ten months, following a gradual decline in the preceding months.
-   The global landscape experienced ongoing crises throughout the year, significantly impacting the foreign exchange market. Consequently, the Australian dollar's descent was not unexpected. The Reserve Bank of Australia (RBA) clarifies that Australia employs a floating exchange rate system, where the Australian dollar's value is determined by the interplay of supply and demand in the foreign exchange market.
-   On the domestic front, factors such as interest rates and inflation figures also play a pivotal role in shaping the Australian dollar's performance on the global currency stage. In comparison to the USD, which boasts even higher interest rates and inflation rates than Australia, the AUD has displayed a consistent decline, with sporadic upticks, over the course of the past year.

![enter image description here](https://github.com/Stephadey/Images/blob/main/Image-4.png?raw=true)

**How the AUD is performing currently:**

-   There are 22 countries with currencies stronger than AUD and 137 countries with currencies weaker than AUD.
![enter image description here](https://github.com/Stephadey/Images/blob/main/Image-5.png?raw=true)
![enter image description here](https://github.com/Stephadey/Images/blob/main/Image-6.png?raw=true)
-   Overall, AUD is stronger than 85% of the world's currencies.

## How to execute the code
This guide will walk you through setting up and running an analysis on currency exchange rate data using the Exchange Rate API. To access the API and run the code, you'll need to follow the steps outlined below.

**Prerequisites**
1. **Sign up on the Exchange Rate API website:** [Exchange Rate API](https://www.exchangerate-api.com/)
2. **Create a .env file:**
    - Create a file named `.env` in the project directory.
    - Add the following line to the file, replacing `<YOUR_API_KEY>` with your API key obtained from the Exchange Rate API website:
      ```
      api_key=<YOUR_API_KEY>
      ```

**Upgrade to "Pro" Plan**
- Upgrade your plan to "Pro" on the Exchange Rate API website to access advanced features and extended analysis capabilities.
- This plan will be valid for 2 months, and no payment information is required.

**Code Usage**
1. **Clone the Repository**

**Install dependencies as needed**
pip install -r requirements.txt

**Run the Analysis**

1. **Open the Jupyter Notebook or Python script:**
   - Navigate to the directory where your Jupyter Notebook containing the analysis code is located.

2. **Ensure the .env file is configured:**
   - Create a file named `.env` in the project directory.
   - Open the `.env` file and set your API key as follows:
     ```dotenv
     api_key=your_api_key_here
3. **Run the code:**
   - Execute the code to fetch exchange rate data and perform the analysis.


## References
- ExchangeRate-API Documentation. Retrieved from [https://www.exchangerate-api.com/docs/overview](https://www.exchangerate-api.com/docs/overview)
- Matplotlib. (2012–2023). Dates functionality in Matplotlib. Retrieved from [https://matplotlib.org/stable/api/dates_api.html](https://matplotlib.org/stable/api/dates_api.html)
- Australian Bureau of Statistics. (31/01/2024). Consumer Price Index Australia: Latest release. Retrieved from [https://www.abs.gov.au/statistics/economy/price-indexes-and-inflation/consumer-price-index-australia/latest-release](https://www.abs.gov.au/statistics/economy/price-indexes-and-inflation/consumer-price-index-australia/latest-release)
- Reserve Bank of Australia. Exchange rates and the Australian economy. Retrieved from [https://www.rba.gov.au/education/resources/explainers/exchange-rates-and-the-australian-economy.html](https://www.rba.gov.au/education/resources/explainers/exchange-rates-and-the-australian-economy.html)
