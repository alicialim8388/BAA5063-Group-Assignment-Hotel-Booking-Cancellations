# BAA5063-Group-Assignment-Hotel-Booking-Cancellations
Data Description

## Hotel Booking Cancellation Dataset

### Dataset Description

**Dimensions:** 17 columns × 36,285 rows  
**File Format:** CSV  
**File Size:** ~3 MB  
**Source/Link:** (https://www.kaggle.com/datasets/youssefaboelwafa/hotel-booking-cancellation-prediction/data)

---

### Data Dictionary

| Variable | Type | Description |
|-----------|------|-------------|
| `Booking_ID` | Categorical | Unique booking reference identifier. |
| `number of adults` | Integer | Number of adults included in the booking. |
| `number of children` | Integer | Number of children included in the booking. |
| `number of weekend nights` | Integer | Nights stayed during weekends (Saturday and Sunday). |
| `number of week nights` | Integer | Nights stayed during weekdays (Monday to Friday). |
| `type of meal` | Categorical | Meal plan chosen (e.g., Meal Plan 1, Meal Plan 2, or Not Selected). |
| `car parking space` | Integer | Whether the guest required a car parking space (1 = Yes, 0 = No). |
| `room type` | Categorical | Type of room reserved (e.g., Room_Type 1, Room_Type 2). |
| `lead time` | Integer | Number of days between booking and arrival. |
| `market segment type` | Categorical | Type of market segment (e.g., Online, Offline, Corporate). |
| `repeated` | Integer | Indicates if the guest has previously stayed at the hotel (1 = Yes, 0 = No). |
| `P-C` | Integer | Number of previous cancellations made by the guest. |
| `P-not-C` | Integer | Number of previous bookings that were not canceled. |
| `average price` | Numeric | Average price per room per night (continuous variable, in USD). |
| `special requests` | Integer | Number of special requests made by the guest. |
| `date of reservation` | Categorical | Date the reservation was made. |
| `booking status` | Categorical | Final status of the booking (`Canceled` or `Not_Canceled`). |
