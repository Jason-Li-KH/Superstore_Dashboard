# **US Superstore Dashboard**
![Animation](https://github.com/user-attachments/assets/51ea47b8-6f8b-4952-9dd0-b2abe3bdafe0)
-------
<br>

**📌 Background**

You, the COO of Superstore, wanted to optimize profitability while reducing losses across the business. You asked me, a data analyst, to design a monitoring dashboard to answer one critical question:

  “How is the business performing in terms of growth and profitability, and where are the biggest opportunities or risks?”

<br>

**🎯 Objective**

To address this issue, I developed a dashboard that delivers:
1.	**Executive Performance Monitoring** – At-a-glance KPIs on Orders, Sales, Profit, and Profit Margin, with year-over-year comparisons.
2.	**Exploratory Insights for Strategy** – Drill-down views into Category, Segment, and Region performance, enabling leadership to identify drivers of growth, unprofitable areas, and operational inefficiencies.

But the original question was quite broad. After a discussion with you, we narrowed the scope into five major questions that this dashboard helps answer.

<br>

**🔍 The Five Key Questions**

1.	How is profit changing over time, and are we sustaining growth year over year?
2.	Which product, customer segement, and region generate the most profit, and which consistently lose money?
3.	
4.  Why do we see spikes or drops in profit during certain months or years?
5.  Where should we focus to capture the biggest opportunities or fix the riskiest losses?

<br>

# **Key Insights and Recommendation**
## **❓ Question 1: How is profit changing over time, and are we sustaining growth year over year?**

<table>
  <tr>
    <td>
      <img width="470" alt="image" src="https://github.com/user-attachments/assets/e83811ff-856d-40bb-88a2-276ef25bb33d" />
    </td>
    <td>
      <img width="470" alt="image" src="https://github.com/user-attachments/assets/005446b0-b39e-4bb3-8f2d-1a3d33eb3d3a" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <sub><i>Figure 1. Overall Profit Trend and Monthly Volatility (2014–2017)</i></sub>
    </td>
  </tr>
</table>

<br>

<table>
  <tr>
    <td>
      <img width="310" alt="image" src="https://github.com/user-attachments/assets/26c5197c-2724-4b8c-bcf1-cde638361ade" />
    </td>
    <td>
      <img width="310" alt="image" src="https://github.com/user-attachments/assets/575eeb04-3cdd-4925-893b-593edb1c90a6" />
    </td>
    <td>
      <img width="310" alt="image" src="https://github.com/user-attachments/assets/8ff1197d-dfbc-4824-aade-2d2b902db9e4" />
    </td>
  </tr>
  <tr>
    <td colspan="3" align="center">
      <sub><i>Figure 2. Profit Volatility by Category, Region, and Segment</i></sub>
    </td>
  </tr>
</table>

**📊 Key Insights**
- **Steady Growth of Profit:** Profit has grown consistently year after year, reaching $92.4K in 2017, with +12.7% growth compared to 2016. This indicates a healthy topline expansion.
- **High Volatility Within Years:** Despite annual growth, monthly profit trends reveal sharp fluctuations, with frequent spikes and dips. This suggests instability in profitability at a more granular level. 
- **Volatility Across Dimensions:** Profit swings are concentrated in specific areas — Technology (Copiers, Machines), certain regions (Central, West), and segments (Corporate, Home Office).

**✅ Recommendation**
- Dive deeper into the underlying factor of fluctuations.
- Prioritize stabilizing volatility by tightening controls on high-risk products, regions, and segments to sustain consistent profit growth.

<br>

## **❓ Question 2: Which product, customer segement, and region generate the most profit, and which consistently lose money?**

<!-- Group: Category, Sub-Category, and Product -->
<table>
  <!-- Top row: Category and Sub-Category side by side -->
  <tr>
    <td>
      <img width="430" alt="Category Chart" src="https://github.com/user-attachments/assets/83ad4a12-6085-4777-b366-f0c6c522322b" />
    </td>
    <td>
      <img width="430" alt="Sub-Category Chart" src="https://github.com/user-attachments/assets/9c43bda3-1a43-427c-94ab-37a3a59ec2fa" />
    </td>
  </tr>
  <!-- Bottom row: Product chart spanning across -->
  <tr>
    <td colspan="2" align="center">
      <img width="865" alt="Product Chart" src="https://github.com/user-attachments/assets/8ba3ac63-a9a1-4a15-842a-98fa759bcb1b" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <sub><i>Figure 3. Profit by Category, Sub-Category, and Product</i></sub>
    </td>
  </tr>
</table>

<br>

<!-- Group: Segment and Region side by side -->
<table>
  <tr>
    <td>
      <img width="680" alt="Segment Chart" src="https://github.com/user-attachments/assets/0a902300-51ad-4f83-a2c9-9b82a1d2331f" />
    </td>
    <td>
      <img width="200" alt="Region Chart" src="https://github.com/user-attachments/assets/6195a97d-77c2-4d0e-b1ba-072840caf13a" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <sub><i>Figure 4. Profit by Segment and Region</i></sub>
    </td>
  </tr>
</table>

**📊 Key Insights**
- **Technology Leads Profits**: Technology products drive the most profit, led by Copiers and Phones, while Furniture consistently underperforms, with Tables showing significant losses.
- **Consumer as Strongest Contributor**: The Consumer segment is the strongest contributor, while Corporate and Home Office lag behind, highlighting uneven profitability across customer groups.
- **Profit Concentrates in West and East**: The West and East regions generate the majority of profits, whereas the South and Central regions deliver much weaker returns.

**✅ Recommendation**
- **Capitalize on High Performer**: Focus on maximizing profitability by doubling down on high-performing categories (Technology, especially Copiers/Phones)
- **Reassess Underperformer:** while addressing underperforming areas like Furniture (Tables), lagging customer segments, and weaker regions (South, Central).





