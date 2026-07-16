# UPI Fraud Detection & Business Intelligence Dashboard

**Comprehensive analysis of 20,000 UPI transactions with fraud detection, customer behavior insights, and merchant risk profiling.**

**Home Page Dashboard** ([UPI Analysis - HomePage.png](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI%20Analysis%20-%20HomePage.png))

![Transactions Dashboard] ([dashboards/screenshot.png](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-Transaction%20Dashboard.png))

![User Dashboard] ([dashboards/screenshot.png](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-User%20Dashboard.png))

![Merchants Dashboard] ([dashboards/screenshot.png](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-Merchants%20Dashboard.png))

![Fraud Detection Dashboard] ([dashboards/screenshot.png)](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-Fraud%20Analysis%20Dashboard.png)

![AmazonPay-Report Dashboard][(dashboards/screenshot.png)](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-Amazon%20Pay%20Report.png)

![G-Pay-Report Dashboard][(dashboards/screenshot.png)](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-G%20Pay%20Report.png)

![BHIM Report Dashboard][(dashboards/screenshot.png)](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-BHIM%20Reports.png)

![Paytm-Report Dashboard][(dashboards/screenshot.png)](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-Paytm%20Report.png)

![Phonepe-Report Dashboard][(dashboards/screenshot.png)](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-Phonepe%20Report.png)

![WhatsApp Pay-Report Dashboard][(dashboards/screenshot.png)](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-WhatsApp%20Pay%20Reports.png)

![Enterprise Merchants -Report Dashboard][(dashboards/screenshot.png)](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-Enterprise%20Merchant%20Report.png)

![Medium Merchnats -Report Dashboard][(dashboards/screenshot.png)](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-Small%20Merchant%20Report.png)

![Small Merchants-Report Dashboard][(dashboards/screenshot.png)](https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence/blob/main/UPI-Medium%20Merchant%20Report.png)
<!-- Add screenshot later -->

## 🎯 Project Objective
To analyze UPI transaction patterns, identify fraud indicators, and deliver actionable business intelligence for risk management and growth strategy.

## 📊 Key Insights
- **Overall Fraud Rate**: **3.82%** (763 fraudulent transactions)
- **Highest Risk Period**: 1 AM – 5 AM (fraud rate up to **6.3%**)
- **Riskiest App**: WhatsApp Pay (4.35% fraud rate)
- **KYC Impact**: Not Verified users have **62% higher** fraud rate
- **Strongest Signals**: IP Location Mismatch, New Device, High Failed Attempts, Amount Deviation

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Jupyter Notebook**: Exploratory Data Analysis
- **PowerBI**: Interactive Dashboards (KPIs, Heatmaps, Drill-downs)
- **Data Sources**: Transactions, Users, Merchants, Fraud Labels

## 📁 Project Structure
- `notebooks/` → Main analysis notebook
- `data/` → Raw & processed datasets
- `reports/` → Final PDF/DOCX report
- `dashboards/` → PowerBI files + screenshots

## 🚀 Key Features & Deliverables
1. **Executive Summary Report** with business recommendations
2. **Interactive PowerBI Dashboards** (3 pages)
3. **Fraud Pattern Detection** (Temporal, Behavioral, Geographic)
4. **Customer & Merchant Segmentation**
5. **Actionable Recommendations** for fraud reduction (35-50% potential)

## 📈 Business Impact
- Real-time monitoring rules proposed for high-risk scenarios
- Enhanced KYC strategy
- App-specific controls
- ML-ready feature set for future predictive modeling

## 🔍 How to Run
```bash
# Clone repo
git clone https://github.com/MohamedNalif/UPI-Fraud-Detection-Business-Intelligence

# Install dependencies
pip install -r requirements.txt

# Open notebook
jupyter notebook notebooks/UPI_Transaction_Analysis.ipynb
