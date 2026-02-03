### Project 2: IQB Analytics Dashboards - ISP Performance Insights and Comparisons

**Difficulty**: 🔴 Hard (350 hours)  
**Mentor(s)**: Pavlos Sermpezis, Roberto D'Auria, Simone Basso  
**Skills Required**: Python, Data Visualization (Plotly), Streamlit, Pandas  
**Skills Preferred**: Geographic data visualization, BigQuery/SQL, UX/UI design, Statistics

#### Description

The Internet Quality Barometer (IQB) is M-Lab's comprehensive framework for measuring Internet performance across various use cases (web browsing, video streaming, gaming, etc.). Unlike simple "speed tests," IQB calculates a composite score reflecting the quality of Internet experience holistically. Currently, IQB has a prototype Streamlit application for applying the framework, but it lacks comprehensive dashboards for analyzing and comparing ISP performance across geographic regions.

This project involves extending the IQB platform by creating interactive, user-friendly dashboards that provide actionable insights into ISP performance. You'll design and implement visualizations that allow users to compare ISPs within countries and cities, identify performance trends, and make informed decisions about Internet service quality. The dashboards should serve multiple user personas: consumers choosing ISPs, researchers studying Internet quality, policymakers monitoring infrastructure, and ISPs benchmarking their performance.

You'll work with M-Lab's extensive measurement dataset, implement statistical aggregations, create interactive geographic visualizations, and design intuitive comparison tools. This is an opportunity to impact how millions understand and choose their Internet services based on real measurement data.

#### Expected Outcomes

- **ISP Performance Dashboard**: Create a comprehensive dashboard showing ISP performance metrics (IQB score, latency, throughput, packet loss) with time-series trends, percentile distributions, and sample size indicators
- **Geographic Comparison Tool**: Build interactive map-based visualizations showing ISP performance across countries, regions, and cities with drill-down capabilities and geographic heatmaps
- **ISP Head-to-Head Comparison**: Implement a side-by-side comparison feature allowing users to compare 2-5 ISPs across multiple metrics with statistical significance testing
- **Use Case Performance Analysis**: Create specialized views showing how ISPs perform for specific use cases (video streaming, gaming, video conferencing, web browsing) based on IQB's multi-dimensional framework
- **Data Export and Reporting**: Add functionality to export visualizations, generate PDF reports, and download filtered datasets for further analysis
- **User Experience Design**: Design an intuitive interface with responsive layouts, clear data presentation, and guided workflows for different user types
- **Performance Optimization**: Implement efficient data caching, lazy loading, and aggregation strategies to handle large M-Lab datasets without lag
- **Documentation**: Create user guides, API documentation, and developer documentation for extending the dashboard system

#### Resources

- [IQB GitHub Repository](https://github.com/m-lab/iqb)
- [Streamlit Documentation](https://docs.streamlit.io/)
