# UPI Fraud Detection & Business Intelligence Dashboard

**Comprehensive analysis of 20,000 UPI transactions with fraud detection, customer behavior insights, and merchant risk profiling.**

![Home Page Dashboard](UPI Analysis - HomePage.png)

![Transactions Dashboard](dashboards/screenshot.png)

![User Dashboard](dashboards/screenshot.png)

![Merchants Dashboard](dashboards/screenshot.png)

![Fraud Detection Dashboard](dashboards/screenshot.png)

![AmazonPay-Report Dashboard](dashboards/screenshot.png)

![G-Pay-Report Dashboard](dashboards/screenshot.png)

![BHIM Report Dashboard](dashboards/screenshot.png)

![Paytm-Report Dashboard](dashboards/screenshot.png)

![Phonepe-Report Dashboard](dashboards/screenshot.png)

![WhatsApp Pay-Report Dashboard](dashboards/screenshot.png)

![Enterprise Merchants -Report Dashboard](dashboards/screenshot.png)

![Medium Merchnats -Report Dashboard](dashboards/screenshot.png)

![Small Merchants-Report Dashboard](dashboards/screenshot.png)
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
