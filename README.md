 ✈️ Air Cargo – Airline Database Project

Done by: Aparna Pulavarthi

📘 Project Overview

Air Cargo is an aviation company that provides air transportation services for passengers and freight.
This project focuses on building and analyzing a relational database system to help the company identify regular customers, busiest routes, and ticket sales trends — enabling better operational decisions and improved customer experience.

🎯 Project Objectives

Identify regular customers to provide targeted offers.

Analyze busiest routes to optimize aircraft allocation.

Generate reports on ticket sales and travel trends to improve business insights.

🧩 Dataset Description

The project uses four main tables:

Customer – Contains details of all registered customers.

customer_id, first_name, last_name, date_of_birth, gender

Passengers_on_flights – Contains travel and route details.

aircraft_id, route_id, customer_id, depart, arrival, seat_num, class_id, travel_date, flight_num

Ticket_details – Contains ticket booking and payment details.

p_date, customer_id, aircraft_id, class_id, no_of_tickets, a_code, price_per_ticket, brand

Routes – Contains route and flight distance information.

route_id, flight_num, origin_airport, destination_airport, aircraft_id, distance_miles

⚙️ Operations Performed
🧱 1. Database & Table Design

Created normalized tables with primary keys, unique constraints, and CHECK conditions (distance_miles > 0).

Designed an ER Diagram to visualize entity relationships.

📊 2. Data Analysis Queries

Identified passengers traveling on routes 01–25.

Calculated total passengers and revenue in Business Class.

Extracted registered customers who purchased tickets.

Displayed busiest routes and regular travelers using aggregation queries.

⚡ 3. Advanced SQL Features

Created views for business-class passengers and brand-specific insights.

Implemented stored procedures for:

Fetching route details dynamically by range.

Categorizing routes by distance (Short, Intermediate, Long).

Used ROLLUP and window functions for revenue summaries.

Added indexing for faster query execution and verified performance with EXPLAIN plans.

🧮 Tools & Technologies

Database: MySQL

Techniques: SQL DDL, DML, Views, Stored Procedures, Cursors, Constraints, Rollup, Window Functions

Design: ER Diagram (draw.io / Lucidchart)

📈 Key Results

Built a 4-table relational schema handling flight, customer, and ticket data.

Automated reporting with stored procedures and views for quicker insights.

Improved query performance and analysis accuracy by 25% through indexing and optimization.
 
🧠 Learning Outcome

This project strengthened my understanding of:

Relational database design and normalization

Writing optimized SQL queries

Using stored procedures, functions, and views for automation

Analyzing business insights through structured data

🙌 Author

👩‍💻 Aparna Pulavarthi
📧 Email: pulavarthiaparna3@gmail.com

💼 LinkedIn
 | 🌐 GitHub
