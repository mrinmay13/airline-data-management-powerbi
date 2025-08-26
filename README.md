# ✈️ Airline Data Management and Analysis Using Power BI  

## 📌 Problem Statement  
The airline industry operates with numerous complexities, requiring effective data management and insights into flight schedules, passenger details, and ticketing systems.  
This project analyzes airline operations to improve efficiency and customer satisfaction.  

---

## 📊 Datasets Used  
- **Flight Information** → FlightID, FlightNumber, Airline, Destination, Status  
- **Passenger Information** → PassengerID, FlightID, SeatNumber  
- **Ticket Information** → TicketID, FlightID, BookingStatus  

---

## 🎯 Objectives  
- Prepare and clean airline data in Power Query  
- Build relationships using FlightID as the key  
- Perform calculations using DAX  
- Create interactive dashboards for operational insights  
- Configure Row-Level Security (RLS) and scheduled refresh  

---

## ✅ Tasks Completed  
### 1. Data Preparation & Cleaning (10 Marks)  
- Removed duplicates  
- Handled missing values  
- Formatted columns  
📎 *[Screenshot here](./screenshots/powerquery_cleaning.png)*  

### 2. Data Modeling (10 Marks)  
- Built relationships between **Flight, Passenger, Ticket** tables  
- Configured cardinality correctly  
📎 *[Data Model Screenshot](./screenshots/datamodel.png)*  

### 3. Enhanced Data Insights (10 Marks)  
- Classified flights as *Best* or *To Be Improved*  
- Extracted flight number using *Column from Examples*  
📎 *[Transformed Data Screenshot](./screenshots/transformed_data.png)*  

### 4. DAX Calculations (10 Marks)  
- Total passengers per flight  
- Total tickets booked  
- Filtered table showing only *Best Flights*  
📎 *[DAX Results](./screenshots/dax_calculations.png)*  

### 5. Visualizations & Interactivity (20 Marks)  
- Passenger count by airline  
- Ticket booking statuses  
- Flights by airline and destination  
- Added slicers for Airline & Destination  
📎 *[Dashboard Visuals](./screenshots/dashboard_visuals.png)*  

### 6. Final Dashboard & Power BI Service (20 Marks)  
- Published dashboard to Power BI Service  
- Configured **Row-Level Security** (RLS) for Airline A  
- Scheduled refresh at **5 PM daily**  
📎 *[Published Dashboard](./screenshots/published_dashboard.png)*  

---

## 📂 Repository Structure  
