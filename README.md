# Baggage Add on Analysis
Airline ticketing transactions include optional baggage add-ons that contribute additional revenue. This analysis focuses on baggage add-on patterns, key routes, and potential issuance errors that may result in revenue loss and operational inefficiencies.

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

