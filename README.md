# Hotel_Booking_Data

## Hotel Booking Data
Data Source: https://www.kaggle.com/mojtaba142/hotel-booking

This dataset contains data from two different hotels in Portugal. It contains 1119390 observations for a 'City Hotel' and a 'Resort Hotel'. From the publication: "Each observation represents a hotel booking between the 1st of July 2015 and 31st of August 2017, including booking that effectively arrived and booking that were canceled."

## Content
1. Import libraries/Clean
* Import Libraries
* Clean 
2. EDA
### Questions to explore through EDA:

1. Where do the guests come from?

![Visitor_Country_of_Origin](https://user-images.githubusercontent.com/71391244/132026109-c4f58f5d-2a82-4c53-9c12-db816215894f.png)

2. What is the Average Daily Rate (ADR)?
![ADR_Per_Unit_Type](https://user-images.githubusercontent.com/71391244/132026234-7450cc1a-985a-4cee-be07-e9b6ba7b0a48.png)

3. Are certain time frames busier? e.g. seasonality
![2016_Daily_Arrivals](https://user-images.githubusercontent.com/71391244/132026405-03771f35-0e0b-4e28-819d-f0f12be9cbd4.jpg)

4. How does the ADR vary in regards to seasonality?
![2016_Daily_Rates](https://user-images.githubusercontent.com/71391244/132026528-aa0d8642-3851-4bc9-b50f-952706275292.jpg)

5. What is the length of stay frequency?
![Stay_Duration_Seasonality](https://user-images.githubusercontent.com/71391244/132027934-99000c7b-c20f-431d-832b-1f12810dd760.png)


9. What is the booking curve for each hotel type?
![Resort_Hotel_Booking_Curve_2016](https://user-images.githubusercontent.com/71391244/132026782-676aa8e7-5e80-4528-855d-214dbd88f5ce.jpg)
![City_Hotel_Booking_Curve_2016](https://user-images.githubusercontent.com/71391244/132026789-5ea2b72f-2e40-4515-a114-b3914096e19b.jpg)
The gold vertical line extending from the x-axis on each graph marks the median.
For the Resort Hotel, 96.33% of all bookings are made on, or within, 90.0 days to arrival. For the City Hotel, 84.92% of all bookings are made on, or within, 90.0 days to arrival

11. What is the probability of a reservation being cancelled?

Total bookings cancelled in 2016: 20,206 (36%)

Resort Hotel bookings cancelled in 2016: 4,874 (27%)

City Hotel bookings cancelled in 2016: 15,332 (41%)

Having the date of cancellation would allow us to find the cancellation curve. Depending on the company's policies, it would be reasonable to assume that having a specific 'cancel by 'Y' days prior for full refund' policy would influence the shape of the cancellation curve. Knowing the shape of the cancellation curve would allow us to find 'X'% of reservations that do cancel, cancel at least 'Y' days prior. Adjusting the cancellation policy would influence the shape of the cancellation curve and may reduce the cancellation percentage. Alternatively, adjusting the cancellation policy may have an affect on the frequency of bookings.
