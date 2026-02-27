# IKEA Global Pricing & Premium Strategy Analysis

## 📌 Project Overview
This project analyzes IKEA’s global product catalog (94,225 products across 10 countries) to evaluate pricing strategy, premium positioning, and engagement behavior.

#### The objective was to understand:
  * How premium products are distributed across categories and countries
  * Whether higher price leads to higher engagement
  * Which categories drive the strongest customer interaction
  * How pricing strategy varies geographically

## 🛠 Tools & Technologies
  * Python (Pandas, NumPy) – Data cleaning & feature engineering
  * MySQL – Business focused analytical queries
  * Tableau – Interactive dashboard visualization
  * SQL Window Functions – Ranking & segmentation

## 📊 Dataset
  * 94,225 global IKEA products
  * Multi country product catalog
  * Multiple currencies normalized to INR
  * Engagement measured via product rating count

## 🔧 Feature Engineering
  * Currency normalization to INR
  * Price Tier segmentation (Budget, Mid-Range, Premium)
  * Engagement level classification
  * Premium Ratio calculation using conditional aggregation
  * Applied product count threshold (≥10) to prevent misleading ratios
  * Log-scale transformation for price vs engagement analysis

## 📈 Key Insights
  1. Premium products represent ~33% of the catalog.
  2. Engagement declines as price increases (Budget products show ~3.7× higher engagement than Premium).
  3. Premium concentration is strongest in seating categories (sofas, armchairs, living).
  4. Premium positioning is more dominant in European markets (France, Italy, Germany).
  5. No premium products significantly outperform average engagement at scale.

## 💡 Business Recommendations
  * Focus premium expansion in high-performing seating categories rather than broad catalog premiumization.
  * Improve engagement strategies for premium SKUs (reviews, storytelling, merchandising).
  * Adopt region-specific pricing strategies instead of uniform global pricing.
  * Maintain strong budget segment as engagement & traffic driver.
