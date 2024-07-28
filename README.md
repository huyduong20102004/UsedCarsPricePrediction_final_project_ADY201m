# Used Cars Price Prediction
## Tables of contents
 * [Project Overview](#project-overview)
 * [Problem_statement](#problem-statement)
 * [Requirements](#requirements)
 * [Dataset](#dataset)
 * [Acknowledgements](#acknowledgements)

## Project Overview
The main goal of this project is to develop a machine learning model that can accurately predict used car prices based on various characteristics such as brand, model, year of manufacture, mileage, condition and other related factors:

- Analyze and process data 
- Find a suitable model and build model
- Create a simple flask application
  
## Problem statement 
The used car market is vast and complex, with prices varying significantly based on numerous factors such as make, model, year, mileage, condition, and location. For buyers, determining a fair price for a used car can be challenging due to the multitude of influencing factors. Similarly, sellers may struggle to set a competitive yet profitable price. The lack of standardized pricing mechanisms often leads to uncertainty and potential financial loss for both parties.

## Requirements
This project should be run with these following libraries
- numPy
- pandas
- flask
- sklearn

## Dataset Description

| Number | Column Name          | Description                                                            | Ý nghĩa                                                   |
|--------|----------------------|------------------------------------------------------------------------|-----------------------------------------------------------|
| 1      | Name                 | Car name                                                               | Tên xe                                                    |
| 2      | Location             | Location where the car is sold                                         | Địa điểm nơi xe được bán                                  |
| 3      | Year                 | Year of manufacture of the car                                         | Năm sản xuất của xe                                       |
| 4      | Kilometers_Driven    | Kilometers driven by the car                                           | Số km đã đi của xe                                        |
| 5      | Fuel_Type            | Type of fuel used by the car (CNG, Diesel, Petrol)                     | Loại nhiên liệu xe sử dụng (CNG, Diesel, Petrol)          |
| 6      | Transmission         | Transmission type of the car (Manual, Automatic)                       | Hộp số của xe (Manual - số tay, Automatic - số tự động)   |
| 7      | Owner_Type           | Type of ownership (First owner, Second owner, etc.)                    | Loại chủ sở hữu (First - chủ sở hữu đầu tiên, Second - chủ sở hữu thứ hai, etc.) |
| 8      | Mileage              | Fuel efficiency of the car (km/l or km/kg)                             | Mức tiêu thụ nhiên liệu của xe (km/l hoặc km/kg)          |
| 9      | Engine               | Engine capacity of the car (CC)                                        | Dung tích động cơ của xe (CC)                             |
| 10     | Power                | Power of the car (bhp)                                                 | Công suất của xe (bhp)                                    |
| 11     | Seats                | Number of seats in the car                                             | Số chỗ ngồi trong xe                                      |
| 12     | New_Price            | New price of the car (if available)                                    | Giá mới của xe (nếu có sẵn)                               |

- Dataset used can be also found in Kaggle Dataset [here](https://www.kaggle.com/datasets/avikasliwal/used-cars-price-prediction)

## Acknowledgements
