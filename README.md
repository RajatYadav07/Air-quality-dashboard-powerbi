# 🌍 Air Quality Dashboard - Power BI

A comprehensive and interactive Power BI dashboard designed to analyze, visualize, and understand air quality trends across India. This project provides detailed insights into air quality indicators across different regions, helping stakeholders make data-driven decisions.

---

## 📋 Table of Contents

1. [Overview](#overview)
2. [Project Objectives](#project-objectives)
3. [Dataset Information](#dataset-information)
4. [Project Structure](#project-structure)
5. [Dashboard Features](#dashboard-features)
6. [Key Visualizations](#key-visualizations)
7. [How to Use](#how-to-use)
8. [System Requirements](#system-requirements)
9. [Installation & Setup](#installation--setup)
10. [Data Dictionary](#data-dictionary)
11. [Analysis Insights](#analysis-insights)
12. [Troubleshooting](#troubleshooting)
13. [Author & Contact](#author--contact)

---

## 📊 Overview

This project is a **Continuous Assessment (CA) assignment** that showcases advanced Power BI skills and data visualization expertise. The Air Quality Dashboard presents real-world air quality data from India in an interactive, user-friendly format that enables quick analysis and trend identification.

The dashboard is built on the **India Air Quality Consolidated Dataset**, which contains comprehensive air quality measurements across multiple Indian cities and regions. It combines raw data with powerful analytics to provide actionable insights about air pollution levels and patterns.

---

## 🎯 Project Objectives

- **Analyze Air Quality Trends**: Track and visualize air quality patterns over time across different regions in India
- **Regional Comparison**: Compare air quality metrics between different cities and states
- **Identify Pollution Hotspots**: Pinpoint areas with severe air quality issues
- **Support Decision Making**: Provide data-driven insights for environmental planning and policy decisions
- **Interactive Reporting**: Create a user-friendly dashboard for stakeholders to explore data independently
- **Time-Series Analysis**: Monitor changes in air quality indicators across different time periods

---

## 📁 Project Structure

```
Air-quality-dashboard-powerbi/
│
├── README.md                                    # This file - Complete project documentation
├── Rajat Bi CA.pbix                            # Main Power BI dashboard file (MAIN FILE)
├── Rajat Yadav Power BI report CA2.pdf         # Detailed analysis report (PDF format)
├── Rajat Yadav Power BI report CA2.docx        # Detailed analysis report (Word format)
├── Air quality dataset/
│   └── india_air_quality_consolidated.csv      # Raw dataset (CSV format)
└── Air quality dataset.zip                     # Compressed dataset backup

```

---

## 📈 Dataset Information

### Source
- **Dataset Name**: India Air Quality Consolidated Dataset
- **File Format**: CSV (Comma-Separated Values)
- **File Size**: Comprehensive multi-region data
- **Data Coverage**: Multiple Indian cities and regions with historical measurements

### Data Characteristics
The dataset includes comprehensive air quality measurements with the following characteristics:
- **Temporal Coverage**: Historical air quality measurements across different time periods
- **Geographic Scope**: Multiple locations across India
- **Variables**: Various air quality indicators and measurements
- **Frequency**: Regular monitoring data with consistent measurement intervals

---

## 🎨 Dashboard Features

### 1. **Interactive Visualizations**
   - Dynamic charts and graphs that respond to user selections
   - Multiple visualization types (line charts, bar charts, maps, etc.)
   - Color-coded indicators for quick analysis

### 2. **Filtering & Drill-Down Capabilities**
   - Filter by region, city, or time period
   - Drill-down functionality to explore detailed data
   - Multi-level analysis from macro to micro perspectives

### 3. **Regional Analysis**
   - State-wise and city-wise air quality comparison
   - Geographic distribution of pollution levels
   - Regional performance metrics

### 4. **Time-Series Analysis**
   - Track air quality trends over time
   - Identify seasonal patterns and fluctuations
   - Compare year-over-year changes

### 5. **KPI Dashboard**
   - Key Performance Indicators for quick overview
   - Summary statistics and aggregated metrics
   - Comparative analysis with benchmarks

### 6. **Responsive Design**
   - Optimized for both desktop and mobile viewing
   - User-friendly interface
   - Intuitive navigation and layout

---

## 🔍 Key Visualizations

The dashboard includes the following key visualizations:

- **Regional Air Quality Map**: Geographic visualization showing air quality across different regions
- **Trend Lines**: Time-series plots showing how air quality changes over months/years
- **Comparative Bar Charts**: Side-by-side comparisons between regions
- **Distribution Charts**: Understanding the spread of air quality values
- **Summary Cards**: Quick-view KPIs for major metrics
- **Interactive Filters**: Slice and dice data by multiple dimensions

---

## 💻 How to Use

### Step-by-Step Guide:

1. **Download the Repository**
   ```
   Clone: git clone https://github.com/RajatYadav07/Air-quality-dashboard-powerbi.git
   Or download as ZIP from GitHub
   ```

2. **Open the Dashboard**
   - Launch Power BI Desktop application
   - Click "File" → "Open"
   - Navigate to the repository folder
   - Select `Rajat Bi CA.pbix`

3. **Data Refresh (if needed)**
   - Click "Refresh" in the Home tab
   - Wait for data to load
   - Dashboard will update with latest data

4. **Explore the Dashboard**
   - Use filters to select specific regions or time periods
   - Click on visualizations to drill down into details
   - Hover over data points for additional information
   - Use slicers to customize your view

5. **Export Reports**
   - Use Power BI's export features to save as PDF or image
   - Print reports directly from the dashboard
   - Share specific pages with stakeholders

---

## 🖥️ System Requirements

### Minimum Requirements:
- **Operating System**: Windows 10 or later / macOS 10.14 or later
- **RAM**: 4 GB (8 GB recommended)
- **Storage**: 2 GB free disk space
- **Software**: Power BI Desktop (Free version available at https://powerbi.microsoft.com)
- **Processor**: Intel Core i5 or equivalent

### Software Requirements:
- **Power BI Desktop**: Version 2.100 or later
- **Excel**: Optional (for data review)
- **Web Browser**: For viewing Power BI Service (if published)

---

## 📥 Installation & Setup

### For Windows Users:

1. **Install Power BI Desktop**
   - Download from: https://powerbi.microsoft.com/en-us/desktop/
   - Run the installer and follow on-screen instructions
   - Launch Power BI Desktop

2. **Clone or Download Repository**
   ```powershell
   git clone https://github.com/RajatYadav07/Air-quality-dashboard-powerbi.git
   cd Air-quality-dashboard-powerbi
   ```

3. **Open the Dashboard**
   - Double-click `Rajat Bi CA.pbix`
   - Or open Power BI → File → Open Recent → Select the file

4. **Initial Data Load**
   - Wait for the dashboard to fully load (may take 30-60 seconds)
   - Data will populate from the CSV dataset
   - All visualizations will render automatically

### For macOS Users:

1. **Install Power BI Desktop**
   - Download from Microsoft App Store or https://powerbi.microsoft.com/
   - Install and launch

2. **Clone Repository**
   ```bash
   git clone https://github.com/RajatYadav07/Air-quality-dashboard-powerbi.git
   cd Air-quality-dashboard-powerbi
   ```

3. **Open Dashboard**
   - Launch Power BI Desktop
   - File → Open → Select `Rajat Bi CA.pbix`

---

## 📚 Data Dictionary

| Field Name | Data Type | Description |
|-----------|-----------|-------------|
| Location/City | Text | Name of the city or region being measured |
| Date | Date | Date of the measurement |
| Pollutant Type | Text | Type of air pollutant (e.g., PM2.5, PM10, NO2, etc.) |
| Measurement Value | Numeric | Quantitative measurement of the pollutant |
| Unit | Text | Measurement unit (µg/m³, ppm, etc.) |
| AQI | Numeric | Air Quality Index (0-500 scale) |
| Quality Category | Text | Category (Good, Moderate, Poor, Very Poor, etc.) |
| Region/State | Text | Administrative region or state |

---

## 💡 Analysis Insights

### Key Findings:

- **Regional Variations**: Air quality varies significantly across different regions of India
- **Seasonal Patterns**: Clear seasonal trends visible in air quality measurements
- **Urban vs. Rural**: Urban areas typically show higher pollution levels
- **Trend Analysis**: Observable long-term trends in air quality improvement/degradation
- **Pollution Hotspots**: Specific regions consistently show poor air quality

### Recommended Actions:

1. **For Policy Makers**: Use findings to implement targeted pollution control measures
2. **For Industries**: Identify regions requiring stricter emission standards
3. **For Public**: Use dashboard to check air quality before outdoor activities
4. **For Researchers**: Access raw data for further academic analysis

---

## 🔧 Troubleshooting

### Common Issues and Solutions:

**Issue**: Dashboard won't open
- **Solution**: Ensure Power BI Desktop is installed and updated to latest version

**Issue**: Data not loading
- **Solution**: Check if CSV file is in the correct location and accessible
- Try refreshing: Home → Refresh

**Issue**: Visualizations appear blank
- **Solution**: Wait for data to fully load (may take 1-2 minutes)
- Clear cache: File → Options → Data Load → Clear Cache

**Issue**: Slow performance
- **Solution**: Close unnecessary applications
- Upgrade RAM if below 8GB
- Reduce date range in filters

**Issue**: Connection errors
- **Solution**: Ensure internet connection is stable
- Check file paths are correct
- Verify CSV file hasn't been moved or deleted

---

## 👤 Author & Contact

**Created by**: Rajat Yadav
**Assignment Type**: Continuous Assessment (CA) - Power BI Project
**Date**: 2024
**Purpose**: Educational & Skill Demonstration

### Connect:
- **GitHub**: https://github.com/RajatYadav07
- **Repository**: https://github.com/RajatYadav07/Air-quality-dashboard-powerbi

---

## 📝 License

This project is created for **educational purposes** as part of a course assignment. The data and visualizations are provided for learning and analysis purposes.

---

## 🙏 Acknowledgments

- Data Source: India Air Quality Consolidated Dataset
- Built with: Microsoft Power BI
- Course: Power BI & Data Visualization
- Institution: Academic Assignment

---

**Last Updated**: May 2026
**Version**: 1.0

---

*For any questions, suggestions, or feedback regarding this project, please feel free to reach out or create an issue in the repository.*
