# 📊 Advertising ROI & Predictive Simulator (Task 2)

## 🌟 Project Overview
This project represents **Phase 2** of the Advertising Data Analysis. While Phase 1 focused on past performance, this dashboard is a **Decision Support Tool** designed for Predictive and Diagnostic Analytics. I built an interactive simulation engine that allows stakeholders to forecast sales outcomes by adjusting budget allocations across six different marketing channels.

---

## 🚀 The "Pro" Analytical Concepts Used
As a transition into Data Science, this task incorporates advanced concepts that go beyond basic reporting:

### 1. Linear Regression Logic
Using the advertising dataset, I identified the **Coefficients** (the mathematical weight) of each channel. This tells us exactly how much a \$1 investment impacts the total products sold.
* **Affiliate Marketing:** 4.0 (The most efficient driver)
* **Billboards:** 3.0
* **Social Media:** 2.5
* **TV:** 2.0
* **Google Ads:** 1.5
* **Influencer Marketing:** 1.2 (The least efficient driver)

### 2. Sensitivity (What-If) Analysis
I implemented **DAX Parameters** to create "What-If" scenarios. This allows users to perform sensitivity analysis—testing how the "Target" (Product Sold) reacts when "Features" (Ad Spend) are modified in real-time.

### 3. Diagnostic AI Visuals
By utilizing the **Key Influencers** AI visual, the dashboard automatically identifies and ranks the factors that cause sales to increase, providing statistical evidence for budget shifts.

---

## 📈 Executive Insights
* **Maximum Impact:** Shifting budget from **Influencers** to **Affiliate Marketing** yields a **3.3x higher return** on sales.
* **Efficiency Ranking:** Affiliate Marketing is the primary growth lever, followed by Billboards and Social Media.
* **Strategic Recommendation:** To optimize total sales without increasing the total budget, the company should prioritize Affiliate and Billboard spending while scaling back on Influencer campaigns.

---

## 🛠️ Tech Stack
* **Power BI:** Advanced DAX, What-If Parameters, AI Analytics.
* **Canva Pro:** UI Layout & Neumorphic Component Design.
* **Statistics:** Linear Regression & Correlation Analysis.

---

### 📂 How to View
1. Download the `.pbix` file from this repository.
2. Open in Power BI Desktop.
3. Use the sliders on the left to simulate your own marketing strategy!
