# Hotel-Booking-Analysis

## Project Summary

In this project, We have attempted to analyze a hotel booking dataset and come up with some relevant conclusions which will help the hotel to improve performance. We had perform our analysis in 4 segments
* Booking Wise Analysis
* Customer Wise Analysis
* Cancellation wise Analysis
* RevenueWiseAnalysis                                                  

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.
A dataset containing 119390 records across 32 features has been given with information regarding bookings of two hotels from July 2015 to August 2017.
We explore and analyze the data to discover important factors that govern the bookings by
* Understanding the business task.
* Import relevant libraries and define useful functions.
* Reading data from files given.
* Data inspection.
* Data cleaning.
* Exploratory data analysis, to find which factors affect the bookings and how they affect it.
* Conclusions drawn from analysis

## Business objective

#### To attract the customer and increase the number of booking in hotels.

## Variable Description
The variables and the data it represents are listed below:                    

hotel : Name of the hotel (Resort Hotel or City Hotel)

is_canceled : If the booking was canceled (1) or not (0)

lead_time : Number of days before the actual arrival of the guests

arrival_date_year : Year of arrival date

arrival_date_month: Month of arrival date

arrival_date_week_number : Week number of year for arrival date

arrival_date_day_of_month : Day of arrival date

stays_in_weekend_nights : Number of weekend nights (Saturday or Sunday) spent at the hotel by the guests.

stays_in_week_nights : Number of weeknights (Monday to Friday) spent at the hotel by the guests.

adults : Number of adults among guests

children : Number of children among guests

babies : Number of babies among guests

meal : Type of meals

country : Country of guests (in code)

market_segment : which segments does customer belongs to.

distribution_channel : Name of booking distribution channel through which customers made booking.

is_repeated_guest : If the booking was from a repeated guest (1) or not (0)

previous_cancellations : Number of previous bookings that were cancelled by the customer prior to the current booking

previous_bookings_not_canceled : Number of previous bookings not cancelled by the customer prior to the current booking

reserved_room_type : Code of room type reserved

assigned_room_type : Code of room type assigned

booking_changes : Number of changes/amendments made to the booking

deposit_type : Type of the deposit made by the guest

agent : ID of travel agent who made the booking

company : ID of the company that made the booking

days_in_waiting_list : Number of days the booking was in the waiting list

customer_type : Type of customer, assuming one of four categories

adr : Average Daily Rate, as defined by dividing the sum of all lodging transactions by the total number of staying nights

required_car_parking_spaces : Number of car parking spaces required by the customer

total_of_special_requests : Number of special requests made by the customer

reservation_status : Reservation status (Canceled, Check-Out or No-Show)

reservation_status_date : Date at which the last reservation status was updated

## Conclusion 

1. City hotel has around 61% of booking and mostly perferred by the customers.
2. Highest number of the guest is from Portugal.
3. Most of the booking are made through Travel Agent and Travel Operators.
4. Most of the booking do not required any deposite which tends to high cancellation rate.
5. Most number of bookings are made in the months of July and Augest.
6. Resort hotel has more number of repeating guest compare to city hotel.
7. 85% customer getting same room as per demand.
8. Room Type A is the most preferred room type among travellers
9. Majority of the customer do not required car parking space.
10. From meal we can observe that BB (Bed and Breakfast) is the most preferred meal amongs customers in both the hotels.
11. Almost 33% of the total booking are cancelled and most numbers of booking where cancelled by transient customer.
12. Number of days in waiting list and not assigning the same room to customer does not affect cancellation of bookings.
13. More revenue deal is generated through Direct distribution channel.
14. Increase in a special request help hotel to generate more revenue.
15. In month of May city hotel has high booking price whereas in month of August resort hotel has high booking price.
16. adr and total guest are positively correlated by 39% which conclude that increase in number of guest also increase in adr.
