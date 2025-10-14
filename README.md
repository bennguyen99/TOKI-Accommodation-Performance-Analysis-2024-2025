# TOKI-Accommodation-Performance-Analysis-2024-2025
Data-driven analysis of TOKI Van Long’s hospitality performance (2024–Sept 2025), uncovering trends in sales, bookings, and stay duration.

# Project Background
**Stay TOKI** is a Vietnamese hospitality brand operating four branches across three provinces — Ninh Binh, Hoa Binh, and Vinh Phuc (specifically Tam Dao). At the end of 2023, the company partnered with a booking platform called **EZCloud** to develop an all-in-one booking system that consolidates data from multiple sources, including fan pages, the company website, and OTAs.

This project focuses on data from **TOKI Retreat Van Long** in Ninh Binh, extracted directly from the EZCloud system, covering the period from early 2024 to the end of September 2025.

As the **Data Analyst** on this project, I was responsible for compiling a business report on **sales performance, customer profiles, booking behavior**, and **stay duration** patterns to uncover actionable business insights. The project was **conducted in Vietnamese**, and the **"Ta" room type — a single-bed category — was excluded** from the analysis at the request of the data provider. An English version will be released soon.

The Spreadsheet files I used for data cleaning are in the repository or can be found here.

The report slides for presentation can be found here.

# Data Structure & Initial Checks
The company's main database structure, as seen below, consists of 2 tables, with a total row count of 6,186 records. 

Key columns include ID, Room type, Company, Net Revenue, Arrival Date, Booking Date, Cancellation Status, and Night Spent.

Data was cleaned and aggregated for analysis, excluding the “Ta” room type and test records created by the in-house team for demonstration purposes.

The final table - TOKI_Merged contains 5,193 records.

TOKI Retreat Van Long Dataset Description:
![1](https://github.com/bennguyen99/TOKI-Accommodation-Performance-Analysis-2024-2025/blob/main/Visualizations/Dataset%20Description.jpg)

# Executive Summary
**TOKI Retreat Van Long achieved a moderate 6.2% year-over-year growth in the first nine months, with an occupancy rate of 68.3% and a cancellation rate of 29.9%**. Revenue and occupancy reached their lowest levels in January and peaked during the summer months, likely driven by vacation demand. The An and Mi room types were the primary revenue contributors, together accounting for over 80% of total room revenue.

By sales channel, **Direct and Booking.com remained the two key revenue sources**, generating more than 90% of total sales. Unlike the Direct channel, **Booking.com performed strongest during the low season** (November–December and February–March), increasing sales by roughly 50% while attracting more long-stay guests.

**Long-stay bookings made up only 13% of total reservations**, with most occurring on weekdays (Monday–Wednesday).

In terms of booking performance, **OTA channels—particularly Booking.com—showed significantly higher cancellation rates** (over 50%) compared with Direct bookings (around 20%), raising the overall business cancellation rate to 29.9%. Cancellations were most common among guests who booked well in advance.

# Deep-dive 
