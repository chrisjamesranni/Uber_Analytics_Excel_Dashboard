NCR Ride-Hailing Service Analysis
Project Overview
This project provides a comprehensive analysis of ride-hailing service data from the National Capital Region (NCR). The goal is to uncover trends, identify key performance indicators, and derive actionable insights from a dataset of over 148,000 ride bookings. The analysis focuses on booking patterns, revenue, cancellation reasons, and popular locations to better understand the service's operations.
Dataset
The primary dataset for this analysis is ncr_ride_bookings.csv. It contains detailed information for each ride, including:
 * Booking and Customer IDs
 * Ride status (Completed, Cancelled, Incomplete)
 * Vehicle type
 * Pickup and drop-off locations
 * Ride value and distance
 * Customer and driver ratings
 * Reasons for cancellation
Git LFS (Large File Storage) Setup
Important: This repository uses Git LFS to manage large data files (.csv). To ensure you download the actual data files instead of pointers, you need to have Git LFS installed.
 * Install Git LFS: If you don't have it, download and install it from the official website.
 * Set up LFS: Run git lfs install once per user account to set up Git LFS.
 * Clone the repository: Clone the repository as you normally would:
   git clone [repository-url]

   Git LFS will automatically detect and download the large files during the cloning process. If you have already cloned the repository without LFS, run git lfs pull to download the data files.
Key Insights from the Analysis
 * Total Bookings: 148,767 rides were analyzed.
 * Total Revenue: The service generated over ₹5.1 Crore from these bookings.
 * Cancellation Analysis:
   * Customer Side: The most common reason for cancellation is the "Driver is not moving towards pickup location."
   * Driver Side: The most frequent reasons are "Personal & Car related issues."
 * Popular Locations: The analysis identifies top pickup and drop-off locations, with areas like Ashram and Basai Dhankot showing high activity.
 * Booking Trends: The data was analyzed to understand monthly and hourly booking trends, revealing peak service times.
Files in This Project
 * ncr_ride_bookings.csv: (Tracked via Git LFS) The raw, unprocessed dataset containing all ride booking information.
 * Pivot_tables.csv: A file containing various pivot tables used to summarize the data, such as top drop locations, cancellation reasons, and performance by vehicle type.
 * Analysis.csv: Contains high-level summary metrics and overall statistics derived from the raw data.
How to Use
Once you have cloned the repository with Git LFS, you can open the .csv files using any spreadsheet software like Microsoft Excel, Google Sheets, or a data analysis tool like Python with the Pandas library to explore the data and findings.
