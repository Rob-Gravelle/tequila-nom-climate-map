# Tequila and Temperature

This project analyzes weather patterns in Tequila, Mexico, to support agave farming and tequila production. Using machine learning and data visualization, it forecasts temperatures and identifies climate trends to help farmers optimize harvest timing and improve yields, ensuring high-quality tequila.

## Key Findings
- **Accurate Predictions**: Random Forest model achieves 2.5°F temperature prediction accuracy.
- **Climate Insights**: K-means clustering identifies hot, dry periods ideal for agave ripening and cooler, humid periods for growth.
- **Practical Impact**: Stable temperature windows (68–86°F) could boost agave yields by 5–10% by reducing heat stress.
- **Seasonal Trends**: High solar energy in summer supports agave photosynthesis, while low temperature variability indicates stable conditions.

## Features
- Random Forest model for temperature forecasting
- K-means clustering of weather patterns
- Climate trend analysis: temperature, solar energy, and 30-day rolling variability
- Visualizations in PDF and HTML report formats

## Tools Used
- **R**: RMarkdown, ggplot2, randomForest, cluster, factoextra, lubridate, zoo
- **Python**: pandas, scikit-learn, seaborn, matplotlib
- **Data Source**: Visual Crossing Weather API

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Rob-Gravelle/tequila-nom-climate-map.git
   cd tequila-nom-climate-map

## License
 MIT License. See LICENSE for details.


