#  Airbnb Performance & Market Analysis Dashboard

An interactive Power BI dashboard designed to analyze Airbnb listing performance, market distribution, pricing, ratings, host credibility, and guest review patterns across cities. The project transforms raw listing and review data into meaningful visual insights to support data-driven understanding of the short-term rental marketplace.

## 📌 Project Overview

### Short Description / Purpose

The Airbnb Performance & Market Analysis Dashboard explores listing distribution, property types, pricing patterns, customer reviews, and host characteristics across different markets. Built using Microsoft Power BI, the dashboard presents key performance indicators (KPIs), market comparisons, and trends to help users understand marketplace performance and identify potential areas for further investigation.

The project demonstrates practical skills in data cleaning, data visualization, KPI reporting, and exploratory business analysis.

## 🛠️ Tech Stack

The dashboard was developed using the following tools and technologies:

- 📊 **Power BI Desktop** – Created the dashboard, KPI cards, charts, slicers, and report pages.
- 🧹 **Power Query** – Cleaned, transformed, and prepared the raw dataset for analysis.
- 🧮 **DAX (Data Analysis Expressions)** – Used for measures and calculations where applicable.
- 📈 **Data Visualization & Reporting** – Presented marketplace trends and comparisons through interactive visuals.
- 📄 **PDF Export** – Shared a static version of the report for viewing without Power BI Desktop.

## 📂 Data Source

**Source:** [Maven Analytics Data Playground – Airbnb Listings & Reviews](https://mavenanalytics.io/data-playground/airbnb-listings-reviews)

The project uses Airbnb listing and review data provided through Maven Analytics. The dataset supports analysis of listing characteristics, locations, pricing, ratings, host attributes, and guest review activity.

The data was cleaned and transformed in Power Query before being used to create visualizations and derive insights in Power BI.

## 🎯 Features & Highlights

### 1. Business Problem

Airbnb operates across multiple cities, with listings varying in price, property type, host characteristics, and customer review activity. Analyzing these factors separately can make it difficult to understand how listings are distributed across markets, how prices differ by accommodation type, and which host or customer characteristics may be associated with marketplace performance.

This dashboard brings these dimensions together in one report to make comparisons and patterns easier to explore.

### 2. Goal of the Dashboard

The primary objectives of this project are to:

- Monitor key Airbnb listing and marketplace metrics.
- Explore listing distribution across cities and property types.
- Compare average prices and ratings across market segments.
- Examine review patterns and monthly trends.
- Analyze host characteristics, including Superhost status and verification indicators.
- Present data in a clear, visual format to support exploratory analysis and business understanding.

### 3. Walkthrough of Key Visuals

The dashboard is organized into three pages:

#### 📊 Page 1: Overview

Provides a high-level summary of Airbnb marketplace activity.

- **KPI Cards:** Summarize key metrics, including total listings, cities, hosts, property types, and reviews.
- **New Listing Trend:** Shows how listing activity changes over time.
- **Purpose:** Helps users understand the overall scale of the marketplace and identify changes in listing activity.

#### ⭐ Page 2: Ratings & Market Comparison

Focuses on differences between markets, accommodation types, and host categories.

- **City Market Share:** Compares the distribution of listings across major cities.
- **Superhost Comparison:** Examines differences between Superhosts and non-Superhosts.
- **Average Price by Room Type:** Compares pricing across accommodation categories.
- **Average Ratings by City:** Highlights differences in customer ratings across locations.
- **Purpose:** Supports comparisons of market concentration, pricing, and customer ratings.

#### 💬 Page 3: Reviews & Host Insights

Explores customer review activity and selected host characteristics.

- **Reviews per Reviewer:** Examines review frequency and repeat review patterns.
- **Host Verification & Profile Indicators:** Explores host verification, profile picture availability, and identity verification.
- **Monthly Review Trends:** Helps identify changes in review activity over time and across cities.
- **Purpose:** Provides additional context on customer engagement, host credibility indicators, and possible seasonal patterns.

### 4. Business Impact & Key Insights

The dashboard helps translate listing and review data into observations that may be useful for marketplace analysis.

- **Market Concentration:** Paris, New York City, and Sydney stand out in the city comparisons, highlighting the importance of location-based analysis.
- **Listing Growth:** Listing activity varies over time, with a visible disruption around the COVID-19 period. Further analysis could help distinguish broader market changes from data coverage effects.
- **Review Frequency:** The analysis indicates that approximately 98.8% of reviewers have three reviews or fewer, suggesting that review activity is concentrated among users with relatively limited review counts.
- **Host Trust Indicators:** Host verification and profile-related attributes can be compared to understand the prevalence of these indicators across listings.
- **Data Quality Opportunities:** Unusually high review counts or other outliers may warrant further investigation before drawing business conclusions.

**Potential Business Applications**

- **Market Research:** Compare listing concentration and characteristics across cities.
- **Pricing Analysis:** Explore differences in average prices by accommodation type.
- **Customer Experience Analysis:** Monitor rating and review patterns across markets.
- **Host Analysis:** Examine host attributes alongside listing and review metrics.
- **Further Investigation:** Identify unusual values, changing trends, and areas where additional analysis may be useful.

*Note: These are exploratory observations from the dashboard, not proof of causation or verified business outcomes.*

## 📷 Screenshots / Demo

A PDF version of the dashboard is included to provide a static preview of the report.

- **Dashboard Preview:** `Airbnb_Dashboard.pdf`
- **Report Pages:** Overview, Ratings & Market Comparison, and Reviews & Host Insights.

Open the PDF to view the report pages and their visualizations. The PDF is a static export and does not retain Power BI slicer interactions or cross-filtering.

## 📁 Repository Contents

- `README.md` – Project overview, methodology, and key insights.
- `Airbnb_Dashboard.pdf` – Static report preview exported from Power BI.

## 🚀 Conclusion

This project demonstrates how Power BI can be used to transform raw marketplace data into a structured analytical report. By combining data preparation, KPI reporting, market comparisons, and review analysis, the dashboard provides a foundation for exploring Airbnb listing performance and customer activity across different markets.


