# Share Market Investment Portfolio Time Series Analysis

## Languages and Tools

- **R**: Used for the core time series analysis and data manipulation.
- **TSA package**: For advanced time series models.
- **Markdown**: For writing the report and documentation.

## Overview

This repository contains the analysis of a share market trader's investment portfolio using time series analysis. The project focuses on building predictive models to forecast future market trends based on historical investment data. The analysis includes various time series models to capture trends, seasonality, autocorrelation, and other behaviors in the data.

### Key Learnings

1. **Time Series Fundamentals**: 
   - Understanding stochastic processes, stationarity, and key aspects of time series data such as trend, seasonality, and autocorrelation.
   - Time series modeling differs from traditional machine learning in that we only use the time variable to predict the dependent variable.

2. **Trend and Seasonality Detection**:
   - Learned to identify and model trends (both linear and polynomial) and seasonality using autoregressive and harmonic models. 
   - Investigated how these components affect the model residuals and what it means for the model's performance.

3. **Model Building and Residual Analysis**:
   - Built several models such as linear, parabolic, high-polynomial, and seasonal models to capture different behaviors in the data.
   - Learned how to interpret model residuals (randomness, white noise, autocorrelation) to validate the effectiveness of the model.

4. **Advanced Time Series Models**:
   - Applied cosine and harmonic models to account for both trends and seasonal variations.
   - Explored combinations of models such as cosine + linear models to improve forecast accuracy.

5. **Error and Forecast Analysis**:
   - Learned to perform residuals analysis to check for normality and autocorrelation, ensuring the model is appropriate for the dataset.
   - Generated future predictions using the best-fitting model, even though certain limitations were identified (such as overfitting in some cases).

### Applications and Future Use

This project has equipped me with a strong foundation in time series analysis, which can be directly applied to:
- **Financial Forecasting**: Predicting future stock prices or investment returns based on historical data.
- **Economic and Market Analysis**: Analyzing trends in broader economic indicators or commodities using similar time series models.
- **Business Planning**: Using historical sales or performance data to forecast future outcomes, enabling better decision-making in resource allocation and budgeting.
- **Data Science Projects**: Leveraging these skills for any project where time-dependent data is involved, such as IoT, climate modeling, or any domain with time-based observations.

### How to Use

1. **Requirements**:
   - R programming language
   - TSA package for time series analysis
   - Additional R libraries as specified in the code

2. **Running the Analysis**:
   - Clone the repository to your local machine.
   - Open `Assignment.Rmd` to view the RMarkdown file that contains the complete analysis.
   - Use the included `.csv` dataset to recreate the models and analysis.
