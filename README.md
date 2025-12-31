# Baggage-Add-on-Analysis-in-Flight-Ticketing
Airline ticketing transactions often include optional baggage add-ons that generate additional revenue. This analysis examines baggage add-on patterns, identifies high-impact routes, and highlights areas where issuance errors may lead to revenue leakage and operational inefficiencies. 

**Dataset Description**

The dataset contains simulated flight ticketing transactions with baggage add-ons. The dataset is a simulated ticketing dataset designed to represent real-world airline baggage transactions.

**Objective**

The objectives of this analysis are:
- To analyze baggage add-on transaction patterns by route and airline
- To identify routes with the highest baggage transaction volume
- To detect potential issuance errors
- To provide data-driven recommendations to improve accuracy and revenue

**Tools**
- Google Sheets (data cleaning, pivot analysis, visualization)

**Analysis & Insights** 
1. **Analysis 1 Baggage Transaction by Route**

   ![Baggage Transaction by Route](https://github.com/naelasproject0817/Baggage-Add-on-Analysis-in-Flight-Ticketing/blob/main/transaction%20by%20route%201.png)

Pivot analysis shows that DPS–SIN has the highest number of baggage add-on transactions compared to other routes.

 ![Baggage Transaction by Route](https://github.com/naelasproject0817/Baggage-Add-on-Analysis-in-Flight-Ticketing/blob/main/Revenue%20Bagasi%20per%20Rute%202.png)

The analysis shows that DPS–SIN has the highest baggage add-on transaction volume. This route therefore represents a high-impact area where even small operational issues could result in significant revenue loss.

2.**Analysis 2 — Issued Error by Analysis**

 ![Issued Error by Analysis](https://github.com/naelasproject0817/Baggage-Add-on-Analysis-in-Flight-Ticketing/blob/main/error%20issues%203.png)


  ![Issued Error by Analysis](https://github.com/naelasproject0817/Baggage-Add-on-Analysis-in-Flight-Ticketing/blob/main/Baggage%20Transactions%20by%20Arlines%204.png)

When segmented by airline, Lion Air and Citilink show relatively high baggage transaction volumes across multiple routes. Airlines with consistently high baggage transaction volumes require closer monitoring, as operational errors on these airlines may have a broader financial impact.
 

**Key Insights**
- DPS–SIN is the highest-volume route for baggage add-on transactions
- Higher transaction volume is associated with a higher frequency of issuance errors
- Routes contributing the most baggage revenue also carry the highest operational risk
- Error monitoring should prioritize transaction volume rather than route count alone


**Folder Structure**
- data: raw & processed dataset
- analysis : spreadsheet
- visualization: charts

