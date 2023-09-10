# EXCEL_Operation_Report
Using excel to perform daily operation report
# Table of content
1. Introduction
2. Process
3. Insight & Recommendation
# Introduction
## 1. Business Context
In the operations of airline A - The manager wants to monitor the load factor of each flights on report date 31MAR2023 for the flight in the period of 31MAR2023-30JUN2023 to determine customer behavior then have a prompt price adjustment

Load factor: is a metric used in the airline industry that measures the percentage of available seating capacity that has been filled with passengers, a high load factor indicates that an airline has sold most of its available seats and is preferred over a low load factor
## 2. Dataset
Extract from internal passenger service system
# Process
Extract data from internal passenger service system for requested date
Use formula functions to calculate and add necessary data fields
Build report
![image](https://github.com/linh280999/EXCEL_Operation_Report/assets/144362005/97c94d08-1cf4-48b7-84de-9f2f28c83afc)
# Insight & Recommendation
## Insight:
Early morning and late night flights will be less popular than mid-day flights

Comparing between the two routes Hanoi to Ho Chi Minh city and Hanoi to Nha Trang, we can see the following customer behavior:

HAN-SGN route, customer tend to book close to the flight date => Due to the nature of the HAN-SGN route, it is a business traveler

HAN-CXR route, passenger tend to book far from the flight date which depart on Thursday or Friday and return on Sunday or Monday  => Due to the nature of the HAN-CXR route, mainly tourists tend to plan to travel and book tickets far from the flight date and they usually choose to travel on weekend since they have to work on weekday

Specialy, on national holiday 30/04-01/05/2022:

![image](https://github.com/linh280999/EXCEL_Operation_Report/assets/144362005/3f666755-a01a-4fa5-b067-4987f7bfefe9)

Route HAN-CXR: Passengers tend to depart from Hanoi on 29,30APR2022 and return on 03MAY2022 while route HAN-SGN route is not affected by the holidays
## Recommendation:
Adjust the prices of early morning and late night flights so that the prices are lower than mid-day flights to attract customers to fill flights.

Increase prices for the Hanoi-Nha Trang segment on 29APR and 30APR and Nha Trang - Hanoi segment on 3MAY

While decrease prices or implement stimulus program for the Nha-Trang-Ha Noi segment on 29APR and 30APR and Hanoi-Nha Trang segment on 3MAY because of the low demand
