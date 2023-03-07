# Hotel Booking Analysis

# Abstract:
Hotels are one of the crucial components of the hospitality industry and also the one which adds to the pride of a city, or country. However, the hotel industry is a highly volatile industry and the bookings depend on a variety of factors such as type of hotels, location, seasonality, days of the week, and many more. The pandemic has further aggravated the highly volatile nature of this important industry. This makes analyzing the patterns available in the past data more important to help the hotels plan it better. Using historical data, hotels can perform various campaigns to boost their business. We can use the patterns to predict future bookings using time series. We have done brainstorming to find out insight from the data by using various technologies such as programming i.e. Python (Pandas, Numpy, etc.), data visualization by python libraries like seaborn, matplotlib, etc.

# Introduction:
The hotel industry is one of the main industries that cater to domestic as well as international tourists. It thus accounts for the GDP of the country as well as provides employment to a wide array of people. 
Thus, it becomes crucial to gain insights from the hotel industry data, in terms of revenue generation, enticing tourists, etc.

Herein our capstone project tries to blend data science with the hotel industry. The descriptive form of data analysis wherein we tried to gain insights from the historical data that we had with us.  Also, based on the trend that we observed, we could predict the future trend that may be followed, i.e., the predictive analysis. And finally, if the hotel wants, they can incorporate the insights we got from the data to plan their future course of action, i.e., prescriptive analysis.

# Business Requirement:
The objective is to gain useful insights from the data about the preference of the guests in choosing the type of hotel, which months contribute towards significant revenue contribution, and how various inter-department collaborate to find out ways in increasing the revenue and also enhance the overall experience of the guests, their room choices, the problems that they face, etc.

# Data Summary:
The main objective of exploratory data analysis is to understand the trend and behaviour of guests’ hotel bookings. For that first, we will need to understand what every feature in the data means. The data table consists of 119,390 rows and 32 columns.
We have the following column names provided to us in the dataset. 
•	hotel: Defines the Type of Hotels in the Given Data Set of Hotel Booking       Analysis (Resort hotel and City hotel)
•	is_canceled: Defines the Status of the Booking ( Ex: Cancelled )1 refers to Canceled and 0 suggests Not Canceled 
•	lead_time: Gives us the timing difference between the booking Time and the arrival from the given data set 
•	arrival_date_year: Represents the Year of Arrival of the Visitor (2015, 2016, 2017) 
•	arrival_date_month: Represents the month of Guest ( Visitors ) Arrival From Jan To Dec 
•	arrival_date_week_number: This represents the Week No. of The Visitors Arrival - 1 to 53 
•	arrival_date_day_of_month: This gives the day number of the month when the visitor arrived - 1 to 31 
•	stays_in_weekend_nights: This gives the number of weekend nights, i.e. Saturday and Sunday 
•	stays_in_week_nights: This gives the number of weeknights, i.e., Monday to Friday 
•	adults: This gives the number of adults per booking 
•	children: This gives the number of children per booking 
•	babies: This gives the number of babies per booking 
•	meal: This gives the type of meal preferred. Undefined/SC means no meal package, BB means Bed & Breakfast, HB means Half board (i.e., breakfast & one other meal – usually dinner), FB means Full board (i.e., breakfast, lunch & dinner) 
•	country: This gives the country of origin of the visitor 
•	market_segment: This gives the group of people based on market Direct, Corporate, Online TA, Offline TA/TO, Complementary, Groups, Aviation Where, TA: Travel Agents, TO: Tour Operators 
•	distribution_channel: This mentions the type of distribution channel Direct, Corporate, TA/TO, Undefined, GDS Features (cont.): 
•	is_repeated_guest: This shows repeated customers 1 means repeated customers, 0 means not repeated 
•	previous_cancellations: Represents the number of previous bookings that were cancelled by the customer before the current booking 
•	previous_bookings_not_canceled: Represents the number of previous bookings not cancelled by the customer prior to the current booking 
•	reserved_room_type: Represents the type of room reserved 'C', 'A', 'D', 'E', 'G', 'F', 'H', 'L', 'P', 'B' 
•	assigned_room_type: Represents the type of room whose possession is given at the time of arrival. 'C', 'A', 'D', 'E', 'G', 'F', 'H', 'L', 'P', 'B' 
•	booking_changes: Represents the number of bookings changed 
•	deposit_type: Represents the types of deposit No Deposit, Non-Refundable 
•	agent: Represents the Agent Id 
•	company: Represents the Company Id 
•	day_in_waiting_list: Represents the Number of days the booking was on the waiting list before confirmation 
•	customer_type: This gives us the Type of customer Contract, Group, Transient, Transient-party 
•	adr: means an  average daily rate 
•	required_car_parking_spaces: Number of car parking spaces required by the customer 
•	total_of_special_requests: Number of special requests made by the customer
•	reservation_status: Status of reservation Canceled, Check-Out, No-Show 
•	reservation_status_date: The date at which the last status was updated 

# Conclusion and Insights:
Starting with understanding data, the number of rows, columns, data in each of the columns, using describe the method, etc. After this, we gained useful insights from the Hotel Booking Data Set. 
A few of the insights that we gained are as below:
●	60% of people prefer City hotels and 40% of people prefer Resort hotels.
●	Agent no.9 makes most of the bookings.
●	Transient customer type is more which is 82.4%. The percentage of Booking associated with the Group is very low.
●	27.5% of people cancelled their bookings.
●	79.1% of customer uses Travel Agency (TA)/Tour Operators (TO).
●	Almost 82% of the bookings were not changed by guests.
●	Most of the guests are coming from Portugal, i.e., more than 25,000 guests are from Portugal.
●	The Year 2016 had the highest number of bookings.
●	July and August’s months had the most Bookings. Summer vacation can be the reason for the bookings.
●	Most preferred Room type is 'A'.
●	98.7 % of the guests prefer the "No deposit" type of deposit.
●	City Hotel has the highest ADR. This means City Hotels are generating more revenue than resort hotels. The more the ADR more is the more revenue.
●	For Resort Hotel, ADR is high in the months of June, July, and August as compared to City Hotels.
●	There is a strong propensity for the A, D, and E reserved_room_type.
●	Guests who were assigned the same room which was there at the time of booking, the above Summary clearly depicts that such guests revisited the hotel. 
●	Not Repeated guests are more likely to cancel their bookings.
●	'Direct' and 'Online TA' are contributing the most in both types of hotels.

# Tableau Dashboard Link: 
https://public.tableau.com/app/profile/anil.bhatt2368/viz/TableauProjectI-HotelBooking/DashboardAnalysis
