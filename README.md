# Baggage-Add-on-Analysis-in-Flight-Ticketing
Airline ticketing transactions often include optional baggage add-ons that generate additional revenue. This analysis examines baggage add-on patterns, identifies high-impact routes, and highlights areas where issuance errors may lead to revenue leakage and operational inefficiencies. 

**Dataset Description**

The dataset contains simulated flight ticketing transactions with baggage add-ons. The dataset is a simulated ticketing dataset designed to represent real-world airline baggage transactions.
- Key variables include:
- Booking ID
- Flight date
- Route
- Airline
- Ticket price
- Baggage add-on indicator
- Baggage fee
- Issued error flag


**Objective**

The objectives of this analysis are:
- To analyze baggage add-on transaction patterns by route and airline
- To identify routes with the highest baggage transaction volume
- To detect potential issuance errors
- To provide data-driven recommendations to improve accuracy and revenue

**Tools**
- Google Sheets / Excel

**Key Insights**
- DPS–SIN is the highest-volume route for baggage add-on transactions
- Higher transaction volume is associated with a higher frequency of issuance errors
- Routes contributing the most baggage revenue also carry the highest operational risk
- Error monitoring should prioritize transaction volume rather than route count alone


**Folder Structure**
- data: raw & processed dataset
- analysis : spreadsheet
- visualization: charts

