✈️ Vistara Airlines – ASP.NET MVC Web Application
This is a web-based airline reservation system developed using ASP.NET MVC. It simulates the functioning of Vistara Airlines, offering modules like online booking, cancellations, flight management, and more.

🧰 Technologies Used
ASP.NET MVC (C#)

ADO.NET (for database operations)

SQL Server (VistaraDb)

HTML, CSS, Bootstrap (for UI)

📌 Features
✅ Reservation
Registered customers can book tickets online.

Two payment modes: pay online or at the time of ticket pickup.

❌ Cancellation
Cancel tickets up to 2 hours before journey time.

Auto deduction based on time of cancellation.

Refund amount is handled manually later.

🧍 Customer Detail Manipulation
Customers can postpone bookings by canceling and creating a new one.

System calculates and adds extra charges automatically.

✈️ Flight Management
Admin can add, edit, or delete flight details.

View information about new or canceled flights.

🗃️ Database Schema (VistaraDb)
Includes the following tables:

Bookings

Cancels

EmployeeLogin

Flights

FlightStatus

ManagerLogin

PassengerDetails

🔐 Login Types
Manager Login – Admin access to manage flights.

Employee Login – Staff access to handle booking and flight info.

📷 Screens & Interfaces
Login Page – For Admins and Employees

Home Page – Dashboard after login

Admin Menus – Add, update, or delete flights

Booking Module – Book ticket

Cancellation Module – Cancel tickets with auto fare deduction

Flight Info Module – View flight status and details

📦 How to Run This Project
Clone or download the repository.

Open in Visual Studio.

Restore NuGet packages.

Setup SQL Server and restore the VistaraDb database.

Update connection string in Web.config.

Run the project (Ctrl + F5) and explore the system.

🙋‍♂️ About
This project is built as part of learning ASP.NET MVC with a real-world airline reservation system scenario.


