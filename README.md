# Load Factor Analysis - README

## 📌 Description
This project processes and visualizes airline load factor data, specifically for Delta Air Lines, using data from the U.S. T100 Segment dataset. The script extracts relevant fields, cleans, and processes the data to generate meaningful insights.

## 📊 Data Processing Workflow
1. **📂 Load Data**: Reads CSV files from 2018 to 2024 containing airline segment information.
2. **✈️ Filter for Delta Air Lines**: Extracts records related to Delta Air Lines (Carrier Code: DL).
3. **🌍 Create Market Identifiers**: Constructs unique market identifiers using origin and destination.
4. **🔄 Merge Aircraft Type Descriptions**: Matches aircraft type codes with descriptions from an external dataset.
5. **📈 Calculate Load Factors**: Computes load factors as the ratio of passengers to available seats.
6. **📊 Generate Visualizations**:
   - 📉 Line plots for selected markets.
   - 🔥 Heatmaps for individual markets, aggregated data, and regional analysis.

## 📊 Visualizations
- **📍 Market-Specific Trends**: Time series plots for selected markets (e.g., PVD-ATL, JFK-LAX).
- **📊 Aggregate Heatmap**: A heatmap showing average load factors across all markets.
- **🌎 Regional Analysis**: Heatmaps by region (Atlantic, Domestic, International, Latin America, Pacific, System).

## 🎯 Benefits
- 🚀 Identifies trends in airline capacity utilization.
- 📊 Provides insights for optimizing route performance.
- 🌍 Helps in understanding regional variations in airline efficiency.

## 🛠️ Usage
Ensure that the required CSV files are available in the `T100_Data` directory before running the script. The output visualizations help in analyzing airline performance over time.



