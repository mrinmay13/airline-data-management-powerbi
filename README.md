# ✈️ Airline Data Management and Analysis Using Power BI  

📌 Problem Statement  
The airline industry operates with numerous complexities, requiring effective data management and insights into flight schedules, passenger details, and ticketing systems.  
This project analyzes airline operations to improve efficiency and customer satisfaction.  

---

📊 Datasets Used  
- **Flight Information** → FlightID, FlightNumber, Airline, Destination, Status  
- **Passenger Information** → PassengerID, FlightID, SeatNumber  
- **Ticket Information** → TicketID, FlightID, BookingStatus  

---

🎯 Objectives  
- Prepare and clean airline data in Power Query  
- Build relationships using FlightID as the key  
- Perform calculations using DAX  
- Create interactive dashboards for operational insights  
- Configure Row-Level Security (RLS) and scheduled refresh  

---

✅ Tasks Completed  
Data Preparation & Cleaning
- Removed duplicates  
- Handled missing values  
- Formatted columns  

 Data Modeling
- Built relationships between **Flight, Passenger, Ticket** tables  
- Configured cardinality correctly  
 
3. Enhanced Data Insights 
- Classified flights as *Best* or *To Be Improved*  
- Extracted flight number using *Column from Examples*  
 
4. DAX Calculations 
- Total passengers per flight  
- Total tickets booked  
- Filtered table showing only *Best Flights*  

5. Visualizations & Interactivity 
- Passenger count by airline  
- Ticket booking statuses  
- Flights by airline and destination  
- Added slicers for Airline & Destination  
  
6. Final Dashboard & Power BI Service
- Published dashboard to Power BI Service  
- Configured **Row-Level Security** (RLS) for Airline A  
- Scheduled refresh at **5 PM daily**  

