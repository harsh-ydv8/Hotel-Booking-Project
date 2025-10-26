# Hotel Booking Data Analysis in Excel

## Project Overview
This project analyzes hotel booking cancellation trends using Excel. Starting from the raw dataset, the workflow includes data cleaning, feature engineering, pivot table reports, and an interactive dashboard to uncover actionable insights.

## Dataset
- **hotel_booking.csv**: Source dataset (cleaned by removing unnecessary columns).
- Original dataset downloaded from Kaggle: [Hotel Booking Dataset](https://www.kaggle.com/datasets/mojtaba142/hotel-booking)
- Columns include hotel type, booking details, guest information, room type, country, reservation status, and more.

## Data Cleaning & Feature Engineering
- Removed irrelevant columns for focused analysis.
- Created new features:
  - **room_status**: Compared 'reserved_room_type' and 'assigned_room_type' (Desired/Un-Desired).
  - **guest_type**: Engineered based on guest composition (adults, children, babies).

## Reporting & Analysis
Six main reports were created using pivot tables (see `/reports` folder):
1. **Guest Type Analysis**: Total guests and cancellations by Couples, Family, Single.
2. **Room Status Cancellations**: Cancellation rates for Desired vs Un-Desired rooms.
3. **Monthly Trends**: Bookings and cancellations for each month.
4. **Hotel Type Booking/Cancelling**: City Hotel vs Resort Hotel statistics.
5. **Hotel Type Report**: Bookings and cancellations split by hotel type.
6. **Top 4 Countries by Cancellation**: Highest cancellations by country (PRT, GBR, FRA, ESP).

## Dashboard
- The Excel dashboard visualizes key metrics:
  - Year slicer (2015/2016/2017)
  - Total bookings & cancellations
  - Pie charts: Bookings and cancellations by hotel type
  - Bar charts: Reservations/cancellations by guest type, month, and room status
  - Top countries by cancellation (horizontal bar chart)
- Sample dashboard image is provided in `/dashboard` folder.

## Instructions
1. Download or clone the repository.
2. Open `hotel_booking_analysis.xlsx` in Excel to explore:
   - Data cleaning steps
   - Pivot table reports
   - Dashboard with interactive slicer
3. View the `/reports` and `/dashboard` folders for report and dashboard images.
4. Cleaned dataset is in `/data/hotel_booking.csv`.

## Insights & Key Findings
- Portugal (PRT) has the highest number of cancellations.
- Couples bookings dominate in both overall numbers and cancellations.
- Most cancellations occur when room assignment matches the reservation ("Desired").
- Peak cancellation months: August and July; lowest: November and December.
- City Hotels have higher bookings and cancellations than Resort Hotels.

## Tools Used
- Microsoft Excel (Pivot Tables, Charts, Dashboard, Slicer)

## Reference
This project was primarily guided by the YouTube tutorial [Data Analytics FULL Course for Beginners to Pro in 29 HOURS - 2025 Edition](https://www.youtube.com/watch?v=VaSjiJMrq24). Additional feature engineering, reports, and dashboard elements were customized.

## Credits
- Dataset: [Hotel Booking Dataset on Kaggle](https://www.kaggle.com/datasets/mojtaba142/hotel-booking)
