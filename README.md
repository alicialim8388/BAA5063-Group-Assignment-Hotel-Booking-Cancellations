# BAA5063-Group-Assignment-Hotel-Booking-Cancellations
Data Description

## Hotel Booking Cancellation Dataset

### Dataset Description

**Dimensions:** 17 columns × 40,060 rows  
**File Format:** CSV  
**File Size:** ~3 MB  
**Source/Link:** (https://www.kaggle.com/datasets/youssefaboelwafa/hotel-booking-cancellation-prediction/data)

---

### Data Dictionary

| Variable | Type | Description |
|-----------|------|-------------|
| `Booking_ID` | Categorical | Unique identifier assigned to each booking record. |
| `no_of_adults` | Numeric | Number of adults included in the booking. |
| `no_of_children` | Numeric | Number of children included in the booking. |
| `no_of_weekend_nights` | Numeric | Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay. |
| `no_of_week_nights` | Numeric | Number of week nights (Monday to Friday) the guest stayed or booked to stay. |
| `type_of_meal_plan` | Categorical | Meal plan chosen by the guest (`Meal Plan 1`, `Meal Plan 2`, or `Not Selected`). |
| `required_car_parking_space` | Binary (0/1) | Whether the guest required a car parking space (1 = Yes, 0 = No). |
| `room_type_reserved` | Categorical | Code of the room type reserved (`Room_Type 1` to `Room_Type 7`). |
| `lead_time` | Numeric | Number of days between the booking date and arrival date. |
| `arrival_year` | Numeric | Year of arrival. |
| `arrival_month` | Numeric | Month of arrival (1–12). |
| `arrival_date` | Numeric | Day of arrival (1–31). |
| `market_segment_type` | Categorical | Type of market segment (e.g., `Online`, `Offline`, `Corporate`). |
| `repeated_guest` | Binary (0/1) | Indicates whether the guest has booked with the hotel before. |
| `no_of_previous_cancellations` | Numeric | Number of previous canceled bookings made by the guest. |
| `no_of_previous_bookings_not_canceled` | Numeric | Number of previous successful bookings by the guest. |
| `avg_price_per_room` | Numeric | Average price per room per night in USD. |
| `no_of_special_requests` | Numeric | Number of special requests made by the guest (e.g., late checkout, view preference). |
| `booking_status` | Categorical | Final status of the booking (`Canceled` or `Not_Canceled`). |
