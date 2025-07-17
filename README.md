# 🚆 Railway Reservation Management System (RRMS)

An ASP.NET-based web application to manage online railway reservations, cancellations, and train schedules. The system supports both administrators and end-users with modules for train and station management, passenger booking, and ticket tracking.

---

## 📌 Project Overview

Railways are one of the most widely used modes of transport in India. This project aims to digitize and streamline the reservation process by providing a fully functional web-based solution for:

- Booking and cancellation of train tickets
- Managing train, route, and station data
- Admin and user modules with secured login
- Viewing train availability and booking history

---

## 🧠 Core Features

### 👤 User Module
- Register and login to book tickets
- Check train availability
- View train schedules and booking history

### 🛠️ Admin Module
- Secure admin login
- Add/update/delete train, route, and station details
- View registered user profiles and passenger bookings

---

## 💻 Tech Stack

| Component         | Technology                      |
|------------------|----------------------------------|
| Frontend         | ASP.NET (Web Forms), HTML, CSS   |
| Backend          | C#                               |
| Database         | SQL Server 2012                  |
| IDE              | Microsoft Visual Studio 2013     |
| Hosting Platform | Windows OS                       |

---

## 🗂 Database Structure

Includes the following tables:

- `Train` — Train ID, Name, Type, Source, Destination, Class
- `Station` — Station ID, Name
- `Route` — Train ID, Station ID, Arrival/Departure Times
- `Booking` — PNR, Date of Journey, Train ID, User Email, Quota, Amount
- `User` — Email, Password, Full Name, Age, Phone, City, State
- `Admin` — User ID, Password
- `Passenger` — PNR, Name, Source, Destination, DOJ, Train ID, Age, Gender

---

## 🖼 Screenshots

> Add screenshots to `/screenshots/` and reference them here:
screenshots/
├── home_page.png

├── user_registration.png

├── admin_login.png

├── booking_page.png

🧪 Testing Summary
Test cases were written and validated for:

Admin login (valid/invalid)

User registration and login

Train booking workflows

Data validation, page redirects, and session management

Testing included:

✔️ Unit Testing

✔️ Integration Testing

✔️ Validation & Verification Testing

✔️ Black Box and White Box Testing

✔️ User Acceptance Testing

🔮 Future Enhancements
Integrate cancellation functionality

Add real-time seat availability tracking

Expand support for multi-country train routes

Enable search/filter options for trains by class, route, or time

👨‍💻 Contributors
A. Bala Keerthimai (18471A05C4)

K. Sruthi (18471A05E5)

G. Sri Gowri Poojitha (18471A05D8)

T. Vishnu Priya (18471A05H8)

Under the guidance of Mr. P. Lakshmi Narayana, M.Tech., Asst. Professor

📚 References
Beginning ASP.NET 3.5 in C# 2008 by George Shepherd

ASP.NET 3.5 Unleashed by Stephen Walther

Software Engineering by Roger S. Pressman

Teach Yourself SQL by Ivan Baron

W3Schools

Google

© 2021 Narasaraopeta Engineering College — Department of CSE

Let me know if you want a `requirements.txt`, `.gitignore`, or help deploying it 
