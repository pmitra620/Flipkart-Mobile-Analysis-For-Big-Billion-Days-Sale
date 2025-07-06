## ![Image](https://github.com/user-attachments/assets/b9488da3-95c1-4ffd-b0a9-c7e23750818f) # Flipkart Mobile Market Analysis – Big Billion Days Edition

This repository presents a data-driven mobile market analysis using Power BI, designed specifically around **Flipkart's Big Billion Days Sale**. The objective is to uncover pricing trends, brand strategies, customer preferences, and performance across various product segments using real-time and historic Flipkart data.

Developed by **Purushottam Mitra**, this project is aimed at helping **business analysts, marketers, and decision-makers** understand product performance during one of India’s biggest online sales events.

> 📌 **Live Dashboard Link**: [https://app.powerbi.com/links/nHgt8ieK4o?ctid=c6e549b3-5f45-4032-aae9-d4244dc5b2c4&pbi_source=linkShare]  
> 📥 **Download Presentation**: [REPORT-Mobile-Market-Trends-A-Data-Driven-Analysis-for-Decision-Makers.pptx](./REPORT-Mobile-Market-Trends-A-Data-Driven-Analysis-for-Decision-Makers.pptx)

---

## 🛒 Business Context

The Flipkart Big Billion Days is a marquee event in the Indian e-commerce calendar. Mobile phones, being the highest-selling category, offer valuable insights into:

- Customer purchase behavior
- Brand performance across price tiers
- Competitive strategies among major players
- Discount and rating dynamics across models

This project bridges **raw market data with visual storytelling**, helping teams align product offerings with market demand.

---

## 🎯 Project Goals

- Analyze product availability across price segments
- Identify top-performing brands and their pricing strategies
- Compare original vs. selling prices and discount trends
- Reveal customer preference based on storage, RAM, and ratings
- Provide strategic recommendations for product and pricing teams

---

## 📦 Dataset Overview

The dataset was scraped from Flipkart’s mobile category and enriched through Power BI's data transformation tools. The primary file used is [`Flipkart_Mobiles - transformed.csv`](./Flipkart_Mobiles%20-%20transformed.csv), with over 3,000 smartphone listings.

| Field               | Description                              |
|--------------------|------------------------------------------|
| Brand              | Mobile manufacturer (e.g., Samsung)      |
| RAM/Storage        | Configuration details                    |
| Price (Original/Selling) | Pre-discount and post-discount price |
| Rating             | Average customer review score            |
| Discount %         | Computed metric for promotional impact   |
| Segment            | Bucketed into Budget, Mid-Range, Premium, Luxury |

> 📁 *Data has been pre-processed using Power Query with dynamic segmentation applied based on price.*

---

## 🧱 Tech Stack

| Tool / Technology       | Role                                     |
|------------------------|------------------------------------------|
| **Power BI Desktop**   | Data modeling and dashboard development  |
| **DAX**                | Custom measures, KPIs, dynamic filters   |
| **Power Query (M)**    | Data cleaning and transformation         |
| **CSV (Excel)**        | Base dataset input                       |
| **Power BI Service**   | Publishing, gateway setup, collaboration |

---

## 📈 Dashboard Features

The Power BI report includes multiple interactive visualizations:

### 💡 Key Insights
- **Samsung** leads with over 700 models, spanning all price segments.
- **4GB RAM / 64GB Storage** is the most offered configuration.
- The **Mid-Range (₹10K–₹30K)** and **Premium (₹30K–₹50K)** dominate product availability.
- **POCO and Motorola** provide the **highest average discounts**, over 14% and 12% respectively.
- **Apple** and **Samsung** contribute the most to total sales value.

### 📊 Visual Highlights
- 📌 Price segmentation: Budget | Mid-Range | Premium | Luxury
- 📌 Brand-wise distribution by segment
- 📌 Rating vs. Selling Price correlation
- 📌 Discount heatmaps by brand
- 📌 Specification combo popularity chart
- 📌 Storage trends by price category

---

## 🧠 Strategic Takeaways

| Topic                          | Insight                                                                 |
|--------------------------------|-------------------------------------------------------------------------|
| Brand Positioning              | Samsung caters to all segments. Apple targets only premium & luxury.   |
| Consumer Preference            | Mid-tier configurations dominate in volume and popularity              |
| Discount Strategy              | Realme and Motorola are aggressively discounting low-range models      |
| Market Opportunities           | Budget-focused brands can expand into mid-tier with 6GB/128GB options  |

---

## 🗂️ Folder Structure

Flipkart-Mobile-Analysis/
│
├── Flipkart_Mobile_Analysis_PURUSHOTTAM MITRA.pbix # Main Power BI report
├── Flipkart_Mobiles - transformed.csv # Cleaned dataset
├── REPORT-Mobile-Market-Trends-A-Data-Driven-Analysis-for-Decision-Makers.pptx
├── Flipkart_Mobile_AnalysisPDF.pdf # PDF summary report
├── README.md
├── /screenshots # Dashboard visuals (optional)
│ ├── overview.png
│ ├── brand_trends.png
│ ├── specs_combo.png
│ └── discount_by_brand.png
└── LICENSE

yaml
Copy
Edit

---

## 📥 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flipkart-mobile-analysis.git
Open the .pbix file in Power BI Desktop.

Explore filters like:

Brand Selector

Price Segment Filter

Memory and Storage Slicer

Ratings Threshold

Optional: Upload to Power BI Service and configure auto-refresh.

📸 Sample Screenshots
View	Preview
Dashboard Overview	
Segment by Brand	
Spec Combo Popularity	
Discounts by Brand	

🧑‍💼 Author
Purushottam Mitra
📧 Email: pmitra620@gmail.com
📱 Phone: +91-7002429620
🔗 LinkedIn
🌐 Portfolio

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

⭐ Show Your Support
If you find this project insightful:

🌟 Star this repository

📣 Share it with your network

🧠 Use the ideas to improve your own analytics projects!

🙏 Acknowledgements
Flipkart for data inspiration

Microsoft Power BI for the platform

Codebasics for the learning framework
