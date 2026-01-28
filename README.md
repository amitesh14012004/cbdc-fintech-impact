# CBDC–Fintech Impact
## Quantifying the Impact of RBI and Media-Based CBDC Sentiment on Indian Fintech and Banking Stocks

---

## Project Overview

This project analyzes how Central Bank Digital Currency (CBDC)–related sentiment derived from RBI communications and media/news coverage influences the stock performance of Indian fintech and banking companies.

By constructing separate sentiment indices for official policy signals and public media narratives, the study quantifies their independent market impact after controlling for standard financial risk factors.

---

## Motivation

India is among the first major economies to launch a retail CBDC (e₹). While the policy objectives are well defined, its market implications for private fintech firms and banks remain uncertain.

This project builds a data-driven framework to examine:
- Whether CBDC developments create opportunities or risks for fintech firms
- How banks respond to CBDC-related announcements
- Whether media narratives differ from official RBI communication in shaping market reactions

---

## Data Sources

- RBI Communications  
  - Press releases, speeches, and official announcements related to CBDC  

- Media and Financial News  
  - CBDC-related articles from Indian and global financial news outlets  

- Market Data  
  - Stock prices of Paytm (fintech), public sector banks, private banks, and selected IT firms  

---

## Methodology

1. Data Collection  
   - Web scraping of RBI websites and financial news portals  
   - Filtering CBDC-related content using keyword-based and NLP techniques  

2. Sentiment Index Construction  
   - Built two monthly CBDC sentiment indices:  
     - RBI-based CBDC Sentiment Index (policy tone)  
     - Media-based CBDC Sentiment Index (news narrative)  
   - Aggregated article-level sentiment into time-series indicators from October 2022 to March 2025  

3. Market Impact Analysis  
   - Examined the separate impact of RBI sentiment and media sentiment on stock returns  
   - Applied the Carhart Four-Factor Model (India) to control for market, size, value, and momentum factors  

---

## Assets Analyzed

- Fintech: Paytm  
- Banking: Public sector banks and private sector banks  
- IT Firms: Selected firms with exposure to digital payments and financial technology  

---

## Key Research Questions

- Do positive or negative CBDC media narratives affect fintech firms differently than banks?
- How do markets respond to official RBI CBDC communication versus media coverage?
- Is CBDC perceived by markets as a competitive threat or a strategic opportunity?

---

## Tools and Libraries

- Python  
- Pandas, NumPy  
- NLP sentiment analysis models  
- BeautifulSoup  
- yfinance  
- statsmodels  

---

## Key Takeaways

- RBI-based and media-based CBDC sentiment capture distinct information channels
- Fintech firms exhibit higher sensitivity to CBDC-related sentiment compared to traditional banks
- Media sentiment reflects public perception and uncertainty, while RBI sentiment reflects policy intent

---

## Author

Amitesh Srivastava  
BS–MS Economics  
Indian Institute of Science Education and Research (IISER), Bhopal
