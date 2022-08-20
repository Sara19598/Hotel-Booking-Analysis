# Hotel-Booking-Analysis
![images](https://user-images.githubusercontent.com/95495685/185741212-11f02384-4377-4646-8853-286820769c3a.jpg)

# INTRODUCTION-
---------------------------------------
A Hotel Booking is the arrangement where people stay to spend their vacations or holidays by paying for rooms,their meals and many more.
The word Booking is described as reserving or blocking a specific room for a guest for a certain period of time which is made as per the request made by the guest while booking. For a guest, reserving a room in advance increases the chances to a great extent to get a nice deal and they will be assured of room on arrival.
Hotel Booking procedure starts with the reservation inquiry, checking the room availability,reservation source,cancellations,lead time , meal preference and among others.
In this project, we are going to have an overview  and predict the factors which are responsible for Hotel Booking parameters.

# OBJECTIVE-
--------------------------------------------
To study and analyse the best time of Hotel Bookings in a year.
To analyse the optimal stay and price variation over a year .
To predict whether or not hotels received the special requests from customers in proportionality.
To analyse the Hotel Bookings from different parts of the countries.
To study meal preference and Hotel Bookings/Cancellations.
To study the correlation between the variables.

# PROBLEM STATEMENT-
-----------------------------------
In the proposed system , we are going to use the Hotel Booking Analysis database to analyze the best time of year to book a hotel room , to analyze the optimal stay to get the best rate of hotel room and also, to predict the special request received to hotels from customers .
The data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. From it, we can understand the customer's behavior and it might help us make better decisions.

# METHODOLOGY- Exploratory Data Analysis
---------------------------------------------------
Using EDA, we will perform analysis to understand the datasets and to show the visualizations of hotel bookings factors with different features and also hotel booking around the worldwide by the customers.With graphs, we will study the factors which are inter-related with each other.
We will predict whether or not a hotel was likely to receive a disproportionately high number of special requests.

# DATA PREPPING-
-------------------------------------------------
This data  describes  datasets with hotel demand data. One of the hotels is a resort hotel and the other is a city hotel. The datasets share the systematic  structure, with 32 variables describing the 119390 observations. Each observation represents a hotel booking. Both datasets comprehend bookings due to arrive between the 1st of July of 2015 and the 31st of August 2017, including bookings that effectively arrived and bookings that were canceled. Since this is hotel real data, all data elements pertaining hotel or customer identification were deleted. Due to the scarcity of real business data for scientific and educational purposes, these datasets can have an important role for research and education in revenue management, machine learning, or data mining, as well as in other fields.

# CHALLENGES FACED-
-----------------------------------------------
Size: The size of the dataset right away is the strength as well as the most challenging aspect of this dataset. Although there are 32 fields that describe every factor, it’s only natural that such a wide range of information may not be available for every Hotel Bookings. This results in a large number of NAN values. 

NaN values: NaN values in the dataset had to be cleaned up accordingly. For instance NaN values in Numerical and categorical fields like agent, company ,country and children were filled with 0. NaN values in textual fields like company for instance were filled with ‘unknown’.

Country Map :- As we have wide data ,to map the country with respect to the number of guests of Hotels was a little tricky task to match the parameters correctly. Finally after some trials , using the reset index command we got the Folium map. 

# APPROACH USED-
-------------------------------------------------------------
As the data includes 32 columns which are both numerical and categorical.To perform the analysis and different visualizations of factors associated with the hotel booking,we performed the pre-processing of data which could be removing NAN values or creating a new dataframe itself.
And, decided the factors which are important for analysis from the view of EDA.

## TOOLS USED-
NumPy :- NumPy is an open-source numerical Python library. NumPy contains a multi-dimensional array and matrix data structures. It can be utilized to perform a number of mathematical operations on arrays such as trigonometric, statistical, and algebraic routines.

Pandas :- Pandas is a useful library in data analysis. It can be used to perform data manipulation and analysis. Pandas provide powerful and easy-to-use data structures, as well as the means to quickly perform operations on these structures.

Matplotlib :-Matplotlib is a Python library that helps in visualizing and analyzing the data and helps in better understanding of the data with the help of graphical, pictorial visualizations that can be simulated using the matplotlib library.

Seaborn :-Seaborn is an open-source Python library built on top of matplotlib. It is used for data visualization and exploratory data analysis. Seaborn works easily with dataframes and the Pandas library. The graphs created can also be customized easily.

Plotly :- The plotly Python library is an interactive, open-source plotting library that supports over 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases.

Missingno :-Missingno is an excellent and simple to use Python library that provides a series of visualisations to understand the presence and distribution of missing data within a pandas dataframe. This can be in the form of either a barplot, matrix plot, heatmap, or a dendrogram.

# ANALYSIS-
---------------------------------------------------------------
## Exploratory Data Analysis-

## 1] Percentage of Hotel Booking-
![download](https://user-images.githubusercontent.com/95495685/185741286-3b740788-1be5-407a-acb8-5b32175ae998.png)

## 2] Best time to book a hotel room in a year-
![download (1)](https://user-images.githubusercontent.com/95495685/185741306-b3d50726-1514-439b-9f54-4be201c8154f.png)

## 3] Price of a hotel room per night-
![newplot (5)](https://user-images.githubusercontent.com/95495685/185741348-0890fdb9-3194-4d8f-a583-8bf05c9a1ee1.png)

## 4] Number of special requests received from customers-
![download (2)](https://user-images.githubusercontent.com/95495685/185741367-fa5b446b-68fc-492f-b45c-122b60e8327b.png)

## 5] Hotel Bookings from different countries-
![newplot (6)](https://user-images.githubusercontent.com/95495685/185741638-96d33019-c806-4661-80b8-5431fe8a4a03.png)

# Descriptive Analysis-
----------------------------------------------------
Descriptive Statistics is summarizing the data at hand through certain numbers like mean, median etc. so as to make the understanding of the data easier. This means that the descriptive statistics are just the representation of the data (sample) available and not based on any theory of probability.

## Count for Hotel type and Meal preference
![AAAA](https://user-images.githubusercontent.com/95495685/185741754-065fa58c-04f6-4fb8-bf45-4ea1cbc1123d.png)

## Correlation between the variables-
![AAAAAAAAAAA](https://user-images.githubusercontent.com/95495685/185741759-80c121f0-2939-4bf1-91a7-3b3d9f1955d0.png)

# CONCLUSION-   
---------------------------------------
The Hotels ultimately want to increase their revenue and they would like to understand and concentrate on each and everything that improves their revenue.The conclusions from my analysis of the data from 2015 to 2017 are :   From the Exploratory Data Analysis-
1. Most of the bookings are done for the City Hotel and the major revenue is from that as well. So the consumer can plan appropriate marketing strategies.
2. The busiest month has been August. So the consumer can be prepared to expect more guests, make necessary arrangements, and do appropriate marketing. Also this helps them understand which months have the least bookings and can plan to give some deals to attract customers in the off season .We should also target months between May to Aug. Those are peak months due to the summer period.
3. The average price daily rate of hotel room per person is high for City Hotel whereas low for Resort Hotel.This shows that hotel bookings are less in Resort Hotel,so they prefer to have a minimum rate.To overcome this , advertisement  should be used by the Hotel marketing strategies.
4. Cancellation rate decreases as the special requests are accomplished.When the customers special requests are fulfilled ,the guests are more likely to stay in the hotel.
5. The most preferred meal type has been Bed & Breakfast. The consumer can be prepared to have more resources for meal time.
6. We also realise that the high rate of cancellations can be due to high no deposit policies.
7. Most visitors are from PRT. This helps the consumer to know his target customers and can attract them during their holiday seasons.
8. To increase the stay at week nights ,hotels should acquire the necessities required by the customers.

# THANK YOU !!!!...
