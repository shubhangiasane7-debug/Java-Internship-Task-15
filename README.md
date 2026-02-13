# Java-Internship-Task-15
Java Internship Task 15 Solution
Multithreading Ticket Booking Simulation
📖 Objective
To simulate a ticket booking system using Java Multithreading.
This project demonstrates:
Creation of multiple threads
Shared resource handling
Race condition concept
Synchronization using synchronized
Thread lifecycle
Thread-safe booking logic
🛠 Tools Used
Java
IntelliJ IDEA / Eclipse
Java Threads
🧠 Concepts Covered
1️⃣ Multithreading
Multiple threads run simultaneously to perform tasks concurrently.
2️⃣ Shared Resource
The tickets variable is shared among all threads.
3️⃣ Race Condition
Occurs when multiple threads access shared data without proper synchronization.
4️⃣ Synchronization
Used synchronized keyword to prevent race condition and ensure thread safety.
5️⃣ sleep()
Used Thread.sleep() to simulate real-time booking delay.
💻 How It Works
A TicketBooking class maintains total available tickets.
Multiple UserThread threads try to book tickets.
The booking method is synchronized to avoid data inconsistency.
If tickets are available → booking successful.
If tickets are not available → booking fails.
▶️ Sample Output
Copy code

Shubhangi is trying to book 2 ticket(s)...
Shubhangi successfully booked 2 ticket(s).
Remaining Tickets: 3
-----------------------------------
Rahul is trying to book 2 ticket(s)...
Rahul successfully booked 2 ticket(s).
Remaining Tickets: 1
-----------------------------------
Priya is trying to book 2 ticket(s)...
Sorry Priya, Not enough tickets available!
-----------------------------------
🎯 Conclusion
This project demonstrates how multithreading works in Java and how synchronization ensures thread-safe operations while accessing shared resources.
