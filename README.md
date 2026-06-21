# NSE & BSE Derivatives Market Analytics Dashboard

## Short Description

The NSE & BSE Derivatives Market Analytics Dashboard is a comprehensive Power BI solution developed to analyze Indian equity and derivatives markets using official NSE and BSE market data. The dashboard combines Stock Delivery Statistics, FII Derivatives Activity, Long-Short Ratios, Open Interest (OI), Change in Open Interest, Futures Positioning, and Market Sentiment Analysis into a single reporting platform.

The solution enables traders, analysts, and market researchers to monitor institutional participation, identify derivative market trends, track open interest accumulation, and analyze stock-specific market behavior through interactive visualizations.

---

## Tech Stack

* Power BI
* Power Query
* DAX
* Microsoft Excel
* NSE Bhav Copy
* BSE Bhav Copy

---

## Data Source

The dashboard integrates multiple datasets from official NSE and BSE sources:

### Data Files

* NSE Derivatives Bhav Copy
* BSE Derivatives Bhav Copy
* Security Bhav Data (Stock Delivery Data)
* FII Derivatives Statistics
* F&O Participant Open Interest Statistics

### Official Sources

* NSE Capital Market Reports
* NSE Derivatives Reports
* BSE Bhav Copy Reports

To maintain repository efficiency, only sample files are included while historical data can be downloaded from official exchange websites.

---

## Business Problem

Market participants often rely on multiple reports to understand market sentiment, institutional positioning, delivery activity, and derivative market behavior. Analyzing these datasets separately can be time-consuming and inefficient.

This dashboard consolidates key equity and derivatives datasets into a single analytical platform, enabling faster market analysis and improved decision-making.

---

## Dashboard Pages

### Landing Page

Provides centralized navigation to all analytical modules.

### Stock Delivery Analysis

Analyzes delivery percentage, number of trades, traded quantity, and stock-wise participation trends to identify accumulation and distribution patterns.

### F&O FII Statistics

Tracks FII derivative activity including total contracts, long positions, short positions, and daily institutional participation.

### Long Short Ratio Analysis

Monitors institutional long-short exposure and ratio trends to evaluate market sentiment and directional bias.

### Index Open Interest Statistics

Analyzes Index Futures and Index Options Open Interest activity across different expiries and trading sessions.

### Stock Open Interest Statistics

Tracks stock-level derivative participation through Open Interest and Change in Open Interest analysis.

### Future Stock OI Statistics

Provides detailed analysis of stock futures positioning and OI accumulation trends.

### Change in Open Interest Statistics

Evaluates OI changes across derivative instruments to identify emerging market opportunities.

### OI Classification Analysis

Classifies stocks into:

* Long Build Up
* Short Build Up
* Long Unwinding
* Short Covering

based on price movement and Open Interest changes.

---

## Key KPIs

* Open Interest (OI)
* Change in Open Interest
* Long Positions
* Short Positions
* Long Short Ratio
* Delivery Percentage
* Number of Trades
* Traded Quantity
* Futures Contracts
* Options Contracts
* Price Change (%)

---

## Key Features

* NSE & BSE Data Integration
* FII Participation Analysis
* Long Short Ratio Tracking
* Open Interest Monitoring
* Change in Open Interest Analysis
* Delivery-Based Stock Analysis
* Index and Stock Derivatives Analytics
* Expiry-Wise Market Analysis
* Dynamic Filtering and Drill-Down Capabilities
* Market Sentiment Classification

---

## Business Impact

This dashboard helps:

* Analyze institutional market participation.
* Track derivative market sentiment.
* Monitor Open Interest accumulation and unwinding.
* Identify Long Build Up and Short Covering opportunities.
* Evaluate stock delivery trends and market strength.
* Support data-driven trading and market research decisions.

---

## Future Enhancements

* Microsoft Fabric Lakehouse Integration
* Parquet-Based Storage Architecture
* Incremental Refresh
* Automated NSE/BSE Data Ingestion
* Historical Market Trend Repository
* Advanced Market Sentiment Analytics
