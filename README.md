# cbdc-fintech-impact
Quantifying the impact of RBI’s CBDC policy on Indian fintech and banking stocks using NLP and financial data
# Quantifying the Impact of RBI's CBDC on Fintech & Banking Stocks

This project analyzes how news and policy signals from the Reserve Bank of India (RBI) related to Central Bank Digital Currency (CBDC) affect Indian fintech and banking companies.

## Motivation
India is one of the first major economies to launch a retail CBDC (e₹). However, its impact on private fintech firms and banks is not well understood. This project builds a data-driven framework to quantify that impact.

## Data Sources
- RBI press releases and speeches related to CBDC  
- Financial news articles mentioning CBDC  
- Stock prices of Paytm and major Indian banks  

## Methodology
1. Web scraping of RBI and news websites  
2. Filtering CBDC-related articles using keyword and NLP models  
3. Construction of a CBDC Sentiment Index  
4. Event-study and regression analysis to measure impact on:
   - Paytm (fintech)
   - Major Indian banks  

## Key Questions
- Does positive CBDC news benefit or hurt fintech firms?
- How do banks react to CBDC announcements?
- Is CBDC perceived as competition or opportunity by markets?

## Tools & Libraries
Python, Pandas, BeautifulSoup, NLP (transformers / sentiment models), yfinance, statsmodels

## Author
Amitesh Srivastava  
BS-MS Economics, IISER Bhopal
