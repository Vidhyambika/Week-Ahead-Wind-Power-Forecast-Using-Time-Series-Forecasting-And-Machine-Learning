# Week-Ahead-Wind-Power-Forecast-Using-Time-Series-Forecasting-And-Machine-Learning
## 🧑‍💻 Author  & Copyrights
**Vidhyambika SR**  

Note: This is my Undergraduation i.e., B.E - CSE Final year project

<img width="1253" height="628" alt="image" src="https://github.com/user-attachments/assets/bc24f15b-e28f-49a3-a532-53332e03d6a0" />


## Abstract:-
  Wind power generation differs from conventional generation due to the stochastic and intermittent nature of wind. Thus, wind power forecasting plays a key role in dealing with the challenges of balancing supply and demand in any electrical system, given the uncertainty associated with the wind farm power output. Accurate wind power forecasting reduces the need for additional balancing, trading energy and reserve power to integrate wind power into the electrical grid. 

This project proposes time-series forecasting using ensemble learning such as Random Forest Regressor, XGBoost regressor, CatBoostRegressor and other machine learning algorithms such as support vector regression, decision tree regression and linear regression. Model performance is evaluated using standard regression metrics such as the R² score, Mean Absolute Error (MAE), and Root Mean Square Error (RMSE) to identify the most accurate algorithms for week-ahead forecasting.

The dataset used in this study consists of two years of wind farm data recorded at 10-minute intervals. It includes meteorological/weather parameters such as temperature, humidity, and pressure, as well as wind-related features including wind speed and wind direction measured at the wind turbine hub height (i.e., to the height of the wheel hub). To enable time-series analysis, the dataset is transformed using a sliding window approach, where data from the previous week is also used as input features to predict wind power output for the subsequent week. Feature engineering techniques are applied to capture temporal dependencies and seasonal patterns in the data.

Experimental results indicate that the Random Forest Regressor and CatBoost Regressor provide the best performance for week-ahead wind power forecasting. These models are deployed on a wind power forecasting website. Additionally, the system supports cluster-based connectivity of wind turbines/wind mills, allowing command signals to be sent during unexpected events and enabling prior notifications to be delivered to users through the platform. Thus, the forecasting results and these features will be useful in maximizing revenue to power producers simultaneously benefitting the power utility and maximizing the sale of power output for wind power producers. 

## 🏆 Achievements & Publications
* **IEEE Publication:** [View the research paper on IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10112685)
* **Award:** This project as paper was recognized with the **Best Paper Award** in the International IEEE Conference. [View Award Certificate/Link](https://www.linkedin.com/in/vidhyambika-sr/details/honors/)

## 🔒 Code Availability & Privacy
Please note that the source code is kept **private**. 

## Components
This repository contains:
- Report
- Video
- PPT

## 📬 Contact
Feel free to contact me for any queries regarding this research.

LinkedIn Profile: [S.R. Vidhyambika](https://www.linkedin.com/in/vidhyambika-sr/)

GitHub Profile: [@Vidhyambika](https://github.com/Vidhyambika)
