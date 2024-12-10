# App Performance Analysis Dashboard

## Overview
This project analyzes app performance using Python to process 7 days of app logs data. It provides insights into API performance, error rates, and anomaly detection.

## Key Features
1. Performance Analysis
   - Average and p95 response times per endpoint
   - Error rates and types of errors
   - User experience metrics (% of requests > 1s)

2. Visualization Dashboard
   - Response time trends over time
   - Error rate patterns
   - Endpoint performance comparison
   - Anomaly distribution visualization

3. Anomaly Detection
   - Identifies unusual response time patterns
   - Tracks error rate anomalies
   - Monitors endpoint health

## Key Insights
1. Response Times:
   - Average response times range from 348ms to 472ms
   - /api/search has highest average response time (471.61ms)
   - /api/recommendations has lowest average response time (348.31ms)
   - Only 0.99% of requests take more than 1 second

2. Error Rates:
   - Error rates range from 4.84% to 6.87%
   - /api/search has highest error rate (6.87%)
   - /api/user/profile has lowest error rate (4.84%)

3. Anomalies:
   - All endpoints show low anomaly percentages (<1.5%)
   - /api/search has highest anomaly percentage (1.21%)

## Technical Implementation
- Built using Python
- Uses pandas for data analysis
- Uses matplotlib for creating graphs
- Simple to run and understand

## Future Improvements
1. Add tools to track performance in real time.
2. Use advanced methods to detect unusual patterns.
3. Create user-friendly dashboards for better insights.
4. Analyze different types of errors in more detail.
5. Set up alerts to notify when something unusual happens.

## Setup Instructions
1. Install required packages:
   ```
   pip install pandas matplotlib seaborn numpy
   ```
2. Run all the cells
