## 🏡 Airbnb Performance Dashboard

An interactive Power BI dashboard analyzing global Airbnb performance, including listings, host growth, city-wise performance, ratings, review trends, and seasonality.

## 📖 Overview

This project turns Airbnb listing and review data into a three-page Power BI report covering market growth, city performance, guest ratings, and seasonality. It helps users see where Airbnb is strongest, how guests rate different cities, and when demand peaks.

## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

- **Power BI Desktop** – Main platform used for report creation and visualization.
- **Power Query** – Data transformation and cleaning layer for preparing the CSV data.
- **DAX (Data Analysis Expressions)** – Used for calculated measures, cumulative % (Pareto) logic, and trust-segment calculations.
- **Data Modeling** – One-to-many relationship between Listings and Reviews on `listing_id` for cross-filtering and aggregation.
- **File Format** – `.pbit` template for development and `.png` for dashboard previews.

## 📂 Data Source

Airbnb data on listings and guest reviews across cities worldwide.

- **Listings.csv** – One row per listing: host details, city, neighbourhood, property and room type, price, capacity, Superhost and verification status, and rating scores.
- **Reviews.csv** – One row per review: listing ID, reviewer ID, and review date.

Source:  https://mavenanalytics.io/data-playground/airbnb-listings-reviews

## ✨ Features / Highlights

### Business Problem
Airbnb operates in hundreds of cities, but raw listing and review data makes it hard to see where the platform is growing, which cities guests rate best, how demand changes by season, and how much hosts can be trusted.

### Goal of the Dashboard
To deliver an interactive visual tool that:
- Shows how Airbnb listings and hosts have grown over time
- Compares cities by market share, ratings, and price
- Reveals seasonal review patterns and reviewer behavior
- Measures host trust through identity verification and profile pictures

### Walkthrough of Key Visuals

**Page 1: Overview**
- **KPI Cards** – Total listings, hosts, cities, property types, and reviews.
- **New Listings Over Time (Line Chart)** – Growth by room type (entire place, private room, hotel room, shared room), with a timeline story from introduction to COVID-19.

<img width="503" height="379" alt="Overview" src="https://github.com/user-attachments/assets/e32735b3-c1d0-4487-8cb5-9f0011838075" />
<br>
<br>

**Page 2: Ratings**
- **Market Share by City (Combo Chart)** – Superhost vs. non-Superhost listings with a cumulative % line.
- **Overall Rating by City (Column Chart)** – Ranks cities by average rating.
- **Average Price by Room Type (Bar Chart)** – Compares pricing across room types.
- **Detailed Rating Matrix** – Accuracy, cleanliness, communication, location, and value by city, switched with Overall/Detailed bookmarks.

<img width="503" height="376" alt="Ratings" src="https://github.com/user-attachments/assets/10df3a3b-160e-403d-8f86-3a826532d50a" />
<br>
<br>

**Page 3: Reviews**
- **Seasonality (Ribbon Chart)** – Each city's share of monthly reviews.
- **Review Frequency (Combo Chart)** – How many reviews each reviewer wrote.
- **Host Trust Cards** – % of hosts by identity verification and profile picture status.

<img width="503" height="377" alt="Reviews" src="https://github.com/user-attachments/assets/1c39d0a0-302d-45d9-a5a7-d31ebfd6cd9f" />
<br>

### Business Impact & Insights
- **Market Concentration:** Paris, NYC, and Sydney hold almost half of all listings and **48%** of reviews.
- **Growth Trend:** New listings peaked in **2015**, slowed in 2016–2017 due to regulations, and were halted by COVID-19.
- **Guest Satisfaction:** Mexico City and Rio are rated highest; Hong Kong and Istanbul lowest. Cleanliness and value score lowest overall.
- **Seasonality:** Paris and Rome peak April–August; New York peaks November–December, which helps with pricing and demand planning.
- **Reviewer Behavior:** **98.8%** of reviewers wrote 3 reviews or fewer.
- **Host Trust:** Over two-thirds of hosts are fully verified.

## 👤 Author

**Ishivita Handa** · [GitHub](https://github.com/ishi1008) · [LinkedIn](https://linkedin.com/in/ishivitahanda)

