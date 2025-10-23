# Delhivery Logistics Data Analysis - Power BI Dashboard

## 📊 Project Overview

This project presents a comprehensive analysis of Delhivery's logistics and supply chain operations using Power BI. Delhivery is one of India's leading logistics and supply chain companies, and this analysis focuses on delivery efficiency, route optimization, delay patterns, and overall operational performance.

## 🚚 About Delhivery

Delhivery is a major logistics and supply chain company in India that provides end-to-end supply chain solutions including warehousing, transportation, and technology services. This dataset contains detailed shipment data that enables deep insights into their operational efficiency and delivery performance.

## 📋 Dataset Description

The dataset contains detailed logistics and shipment data with key attributes related to:
- Shipment tracking and delivery performance
- Customer locations and route information  
- Operational metrics and timing data
- Service quality and customer satisfaction indicators

### Key Metrics Analyzed
- **Total Shipments**: 32.71M shipments processed
- **Total Distance Covered**: Comprehensive route coverage analysis
- **Average Delivery Time**: 574.01 time units
- **On-Time Delivery Rate**: 86.14%
- **Delayed Shipments**: 13.86%

## 🔍 Dataset Features

| Feature | Description |
|---------|-------------|
| **Order ID** | Unique identifier for each shipment |
| **Shipment Date** | Date when the order was shipped |
| **Delivery Date** | Date when the shipment was delivered |
| **Origin City/State** | The source location of the package |
| **Destination City/State** | The final delivery location |
| **Courier Partner** | The logistics partner handling the delivery |
| **Delivery Status** | Whether the package was delivered on time, delayed, or undelivered |
| **Payment Mode** | Whether the order was prepaid or cash-on-delivery (COD) |
| **Shipment Weight** | The weight of the package in kg |
| **Transit Time** | Time taken for delivery from the origin to the destination |
| **Customer Rating** | Feedback score provided by customers |
| **Delay Reason** | If applicable, reasons for delivery delays (e.g., weather, traffic, incorrect address) |

## 📈 Power BI Dashboard Components

### 1. **Key Performance Indicators (KPIs)**
- Total Shipment Count
- Total Distance Covered  
- Average Delivery Time
- On-Time Delivery Percentage
- Delayed Shipments Percentage

### 2. **Operational Analysis Charts**
- **Cutoff Analysis**: Distribution of delivery cutoff times
- **Route Type Analysis**: Breakdown of FTL (Full Truck Load) vs Carting operations
- **OSRM vs Actual Time**: Comparison between planned and actual delivery times
- **OSRM vs Actual Distance**: Route optimization analysis

### 3. **Time-Based Analytics**
- **Daily Performance**: Day-of-week delivery performance trends
- **Trip Count by Day and Route Type**: Operational volume patterns
- **Start Scan to End Scan Distribution**: Process timing analysis
- **Average Delivery Time by Day**: Weekly performance variations

### 4. **Performance Tracking**
- Weekly delivery success rates across different days
- Route type efficiency comparisons
- Distance vs time optimization metrics

## 🛠️ Tools & Technologies

- **Power BI Desktop**: For dashboard creation and data visualization
- **Data Source**: Delhivery logistics dataset
- **Analysis Type**: Descriptive and diagnostic analytics
- **Visualization Types**: KPI cards, bar charts, line graphs, pie charts, heatmaps

## 📊 Key Insights

### Operational Performance
- Achieved **86.14% on-time delivery rate** across 32.71M shipments
- **13.86% delayed shipments** indicating areas for improvement
- Comprehensive route coverage with detailed distance tracking

### Route Efficiency
- **FTL (Full Truck Load)** operations show consistent performance patterns
- OSRM (Open Source Routing Machine) analysis reveals optimization opportunities
- Clear correlation between planned vs actual delivery metrics

### Temporal Patterns
- Performance varies by day of the week
- Thursday and Sunday show different delivery time patterns
- Start-to-end scan distribution provides process optimization insights

## 📁 Project Structure

```
delhivery-logistics-analysis/
│
├── README.md                          # Project documentation
├── data/
│   └── delhivery_data.csv             # Raw dataset (if available)
├── dashboard/
│   └── delhivery_dashboard.pbix       # Power BI dashboard file
├── images/
│   └── dashboard_screenshot.png       # Dashboard visualization
└── docs/
    ├── data_dictionary.md             # Detailed feature descriptions
    └── analysis_methodology.md        # Analysis approach documentation
```

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (latest version)
- Microsoft Excel (for data preprocessing if needed)
- Basic understanding of logistics and supply chain metrics

### Setup Instructions

1. **Download Power BI Desktop**
   - Install from Microsoft Store or official website
   - Ensure you have the latest version for compatibility

2. **Open the Dashboard**
   - Open the `.pbix` file in Power BI Desktop
   - Allow data refresh if prompted
   - Navigate through different dashboard tabs

3. **Data Refresh**
   - If working with live data, configure data source connections
   - Set up automatic refresh schedules if needed

4. **Customization**
   - Modify visualizations based on specific requirements
   - Add new metrics or KPIs as needed
   - Adjust filters and slicers for focused analysis

## 📈 Analysis Methodology

### 1. **Data Preparation**
- Data cleaning and validation
- Missing value treatment
- Date format standardization
- Categorical variable encoding

### 2. **Performance Metrics Calculation**
- On-time delivery rate calculation
- Average delivery time computation
- Route efficiency metrics
- Delay pattern analysis

### 3. **Visualization Design**
- KPI dashboard for executive summary
- Detailed operational charts for analysis
- Interactive filters for drill-down capabilities
- Time-series analysis for trend identification

## 💡 Business Applications

### Supply Chain Optimization
- Identify bottlenecks in delivery processes
- Optimize route planning and resource allocation
- Improve customer satisfaction through better delivery performance

### Operational Insights
- Monitor real-time delivery performance
- Track key performance indicators
- Identify patterns in delays and operational inefficiencies

### Strategic Decision Making
- Data-driven insights for business strategy
- Performance benchmarking against industry standards
- Resource planning and capacity optimization

## 🎯 Future Enhancements

### Advanced Analytics
- Predictive modeling for delivery time estimation
- Machine learning for route optimization
- Customer satisfaction prediction models

### Dashboard Improvements
- Real-time data integration
- Mobile-responsive design
- Advanced filtering and drill-down capabilities
- Automated alert systems for performance deviations

### Data Integration
- Integration with additional data sources
- Weather data correlation for delay analysis
- Customer feedback integration
- Financial metrics incorporation

## 📋 Requirements

### Technical Requirements
- Power BI Desktop (version 2.0 or higher)
- Windows 10/11 or compatible operating system
- Minimum 4GB RAM for smooth performance
- Dataset access permissions

### Data Requirements
- Clean, structured logistics data
- Consistent date formats
- Valid geographical information
- Complete shipment tracking data

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 Screenshots / Demo
Show what the dashboard looks like . -![Alt text](https://github.com/username/repo/assets/image.png)
Sample :  ![Dashboard Preview].(https://github.com/Ishu-2820/Delivery_Delay_Analysis/blob/main/dilveray%20dashborad.png).

## 👥 Author

**[Ishika Kumari]**
- Data Analytics Intern 
- Location: Bihar, India

## 📞 Contact

For questions, feedback, or collaboration opportunities:
- Email: [dk321569@gmail.com]
- LinkedIn: https://www.linkedin.com/in/ishika-kumari-21973732b/
- GitHub: [https://github.com/Ishu-2820]

## 🙏 Acknowledgments

- Delhivery for providing comprehensive logistics data
- Power BI community for visualization best practices
- Open Source Routing Machine (OSRM) for route optimization insights
- Supply chain analytics community for domain expertise

---

**Note**: This analysis is based on historical data and is intended for educational and analytical purposes. Real-world applications should consider additional factors and validation.
