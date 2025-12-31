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

**Analysis** 
1. **Analysis 1 Baggage Transaction by Route**

   ![Baggage Transaction by Route](https://github.com/naelasproject0817/Baggage-Add-on-Analysis-in-Flight-Ticketing/blob/main/transaction%20by%20route%201.png)

Pivot analysis shows that DPS–SIN has the highest number of baggage add-on transactions compared to other routes.

 ![Baggage Transaction by Route](https://github.com/naelasproject0817/Baggage-Add-on-Analysis-in-Flight-Ticketing/blob/main/Revenue%20Bagasi%20per%20Rute%202.png)

The analysis shows that DPS–SIN has the highest baggage add-on transaction volume. This route therefore represents a high-impact area where even small operational issues could result in significant revenue loss.

2.**Analysis 2 — Issued Error by Analysis**

 ![Issued Error by Analysis](https://github.com/naelasproject0817/Baggage-Add-on-Analysis-in-Flight-Ticketing/blob/main/error%20issues%203.png)


  ![Issued Error by Analysis](https://github.com/naelasproject0817/Baggage-Add-on-Analysis-in-Flight-Ticketing/blob/main/Baggage%20Transactions%20by%20Arlines%204.png)

Volume vs. Error Anomaly: Statistical analysis reveals a stark contrast between transaction volume and failure rates. Lion Air exhibits a significantly higher error rate compared to its peers. Conversely, Citilink manages the highest operational volume while maintaining the lowest error frequency.

Technical Conclusion: These results demonstrate that high transaction volume is not the root cause of "issued errors." Instead, the issues appear to be systemic and specific to certain carrier infrastructures. For instance, Lion Air continues to experience frequent failures despite having a lower volume than Citilink, pointing toward internal technical inefficiencies.

 3. **Analysis 3 — Baggage Transaction Volume by Route**

 ![Baggage Transaction Volume by Route](https://github.com/naelasproject0817/Baggage-Add-on-Analysis-in-Flight-Ticketing/blob/main/transaction%20volume%20by%20route%205.png) 
 
 Error analysis reveals that issuance errors occur move frequenlty on routes with higher transaction volume, particularly DPS-SIN
 
 ![Baggage Transaction Volume by Route](https://github.com/naelasproject0817/Baggage-Add-on-Analysis-in-Flight-Ticketing/blob/main/TRANSAKSI%20BAGASI%206.png)

 
This suggests that operational pressure on high-volume routes may increase the likelihood of errors.

**Key Insights**
- DPS–SIN is the highest-volume route for baggage add-on transactions
- Higher transaction volume is not the root cause of errors. Citilink demonstrates superior scalability by handling the highest volume with the lowest error rate (6.06%).
- Lion Air represents a significant operational bottleneck, recording the highest error rate (25.93%) despite having a lower transaction volume than Citilink. This points to carrier-specific technical inefficiencies.
- DPS-SIN is a high-risk, high-value zone due to frequent Lion Air errors, requiring urgent action to stop revenue leakage

**Recommendations**
- Prioritize additional quality control checks on DPS–SIN due to its high baggage transaction volume
- Implement error monitoring dashboards for high-impact routes
- Provide targeted refresher training for agents handling high-volume baggage issuance
- Regularly review baggage issuance performance to reduce revenue leakage
- Optimizing high-volume routes can help reduce issuance errors while protecting baggage revenue

**Conclusion**

By analyzing baggage revenue, transaction volume, and issued error patterns, this project highlights key operational focus areas where process improvements can deliver both efficiency gains and revenue protection.

