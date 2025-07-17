# 🏨 Hotel Reservation System (C++)

A console-based **Hotel Reservation System** written in **C++**, demonstrating core **Object-Oriented Programming (OOP)** concepts like **encapsulation**, **classes**, and **vectors**.

---

## 🚀 Features

- ✅ Book a room with a random room number
- ✅ Cancel a booking using guest info and room details
- ✅ View booking details by room number and type
- ✅ Uses `vector` for storing bookings dynamically
- ✅ Clean and interactive menu-based interface

---

## 🧱 Class Structure

| Class   | Responsibility                                      |
|---------|------------------------------------------------------|
| `Guest` | Stores guest name and contact number                 |
| `Booking` | Handles room type, room number, and guest info     |

- All bookings are stored in a `static vector<Booking>` shared across all instances.

---

## 🖥️ Menu Overview

```text
**** Hotel Reservation System ****
1. Book a Room
2. Cancel Booking
3. View Booking Details
4. Exit
Each option allows user interaction through console inputs.

🧪 Sample Run
mathematica
Copy
Edit
**** Hotel Reservation System ****
1. Book a Room
2. Cancel Booking
3. View Booking Details
4. Exit
Enter your choice: 1
Booking a room...
Enter Room Type: Deluxe
Enter Guest Name: John Doe
Enter Contact Number: 123456789
Room booked! Your room number is: 187
⚙️ Compilation & Run
bash
Copy
Edit
g++ -o hotel_reservation hotel_reservation.cpp
./hotel_reservation
📚 Concepts Practiced
Object-Oriented Programming (Classes, Encapsulation)

Random number generation using rand() and srand()

Input/Output with cin and getline()

Working with vector to manage a dynamic list of bookings

🚧 Limitations
No file saving/loading (data is lost on program exit)

Room numbers are randomly generated without duplication checks

Only one booking operation can be done per loop iteration

✅ Possible Improvements
Save and load bookings to/from a file

Prevent duplicate room numbers

Add price, date, duration, or room availability tracking

📝 License
Free to use for personal learning and educational purposes.
