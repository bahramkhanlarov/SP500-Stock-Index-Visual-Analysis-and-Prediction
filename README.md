
# S&P500 Stock Index Visual Analysis and Prediction

**Author:** Bahram Khanlarov  
**Date:** April 29, 2023


## Project Overview
This project offers a comprehensive visual analysis and prediction of the S&P 500 stock index, which represents the performance of 500 large-cap publicly traded US companies. The analysis commenced with a visual exploration using the MACD indicator. Advanced predictive models, including ARIMA, Prophet, and KNN, were applied to forecast the stock index over a 30-day horizon.

![Visualization from MACD](000016.png)
![Alt text for your image](URL_to_your_image)

## Key Findings
- Out of the models tested, ARIMA(0,1,1) demonstrated the best forecasting capabilities based on RMSE values.
- The research provided valuable insights into the behavior of the S&P 500 index, aiding investors and analysts in making informed decisions.

## Data Source
Data for the S&P 500 index ("^GSPC") was sourced from Yahoo Finance using the `quantmod` package in R.

## Technologies and Packages Used
- R for data analysis and modeling
- `quantmod` for data retrieval
- `forecast` for ARIMA modeling
- `prophet` for the Prophet forecasting model
- `tsfknn` for KNN regression prediction

## How to Run
1. Ensure you have R and the necessary packages installed.
2. Clone the repository.
3. Run the `.Rmd` file in an R environment to replicate the analysis and predictions.

## License
This project is open-sourced under the MIT License. See `LICENSE` for more information.

## Contact
For any queries or feedback, please reach out to [Bahram Khanlarov](mailto:bahram.khanlarov@stud.hslu.ch).
