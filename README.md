*__NCR Ride-Hailing Service Analysis__*

__*Project Overview*__

This project provides a comprehensive analysis of ride-hailing service data from the National Capital Region (NCR). The goal is to uncover trends, identify key performance indicators, and derive actionable insights from a dataset of over 148,000 ride bookings. The analysis focuses on booking patterns, revenue, cancellation reasons, and popular locations to better understand the service's operations.
Dataset The primary dataset for this analysis is ncr_ride_bookings.csv. It contains detailed information for each ride, including:
 * Booking and Customer IDs
 * Ride status (Completed, Cancelled, Incomplete)
 * Vehicle type
 * Pickup and drop-off locations
 * Ride value and distance
 * Customer and driver ratings
 * Reasons for cancellation

*__Git LFS (Large File Storage) Setup__*
Important: This repository uses Git LFS to manage large data files (.csv). To ensure you download the actual data files instead of pointers, you need to have Git LFS installed.
 * *__Install Git LFS:__* If you don't have it, download and install it from the official website.
 * *__Set up LFS:__* Run git lfs install once per user account to set up Git LFS.
 * *__Clone the repository:__* Clone the repository as you normally would:
   git clone [repository-url]

   Git LFS will automatically detect and download the large files during the cloning process. If you have already cloned the repository without LFS, run git lfs pull to download the data files.

*__Key Insights from the Analysis__*
 * *__Total Bookings:__* 148,767 rides were analyzed.
 * *__Total Revenue:__* The service generated over ₹5.1 Crore from these bookings.
 * *__Cancellation Analysis:__*
   * *__Customer Side:__* The most common reason for cancellation is the "Driver is not moving towards pickup location."
   * __*Driver Side:*__ The most frequent reasons are "Personal & Car related issues."
 * *__Popular Locations:__* The analysis identifies top pickup and drop-off locations, with areas like Ashram and Basai Dhankot showing high activity.
 * __*Booking Trends:*__ The data was analyzed to understand monthly and hourly booking trends, revealing peak service times.

__*Files in This Project*__
 
 *__Main_project.xlsx:__* The Excel file is organized into the following sheets:

__*ncr_ride_bookings dataset:*__ The raw, unprocessed dataset containing all ride booking information.

*__Pivot_tables:__* Contains various pivot tables used to summarize the data, such as top drop locations, cancellation reasons, and performance by vehicle type.

__*Analysis:*__ Contains high-level summary metrics and overall statistics derived from the raw data.

*__Revenue:__* A detailed breakdown of revenue streams, booking values, and payment methods.

*__Vehicle Type:__* Analysis of ride counts, revenue, and ratings per vehicle category.

*__Cancellation:__* A deep dive into the reasons for cancellations, segmented by who cancelled (customer vs. driver).

*__Rating:__* A closer look at trends and averages for both driver and customer ratings.


