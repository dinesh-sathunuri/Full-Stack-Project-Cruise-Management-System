# Full-Stack Project: Cruise Management System

## Project Overview  
Nature International Cruise Excellence (NICE) is a cruise management system designed to provide seamless booking, entertainment, and payment solutions for cruise travelers. The system supports features such as trip planning, package selection, and real-time database management to ensure a premium user experience.  

## Technologies Used  
- **Frontend**: React (for dynamic and user-friendly UI)  
- **Backend**: Spring Boot (for RESTful API services)  
- **Database**: MySQL (for structured data management)  
- **Security**: `@Transactional` annotation to ensure atomic operations  
- **Concurrency Handling**: `FOR UPDATE WAIT 15` to prevent deadlocks  

## Features  
- **User Management**: Passenger details, bookings, and payments  
- **Trip & Stateroom Management**: Handling multiple trip packages and stateroom types  
- **Entertainment & Dining**: Restaurant scheduling and entertainment options  
- **Secure Transactions**: Payments processed using MySQL triggers and stored procedures  

## Installation & Setup  
1. Clone this repository:  
   ```bash
   git clone https://github.com/dinesh-sathunuri/Full-Stack-Project-Cruise-Management-System.git
   cd Full-Stack-Project-Cruise-Management-System
   ```  
2. **Backend Setup**:  
   - Install Java 17+ and Maven  
   - Navigate to the `backend` folder and run:  
     ```bash
     mvn spring-boot:run
     ```  
3. **Frontend Setup**:  
   - Install Node.js and navigate to the `frontend` folder  
   - Run:  
     ```bash
     npm install  
     npm start
     ```  
4. **Database Setup**:  
   - Import the MySQL schema (`schema.sql`) and sample data (`data.sql`)  

## How to Use  
- Users can **register, browse trips, select staterooms, and book packages**  
- Admins can **manage bookings, update trip schedules, and handle payments**  

## Contributors  
- Giorgi Merabishvili (GM3386)  
- Dinesh Sathunuri (DS7675)  
- Shreya Reddy (SN3871)  
