# SRP-Single Responsibility Principle

We develop LAN Drivers for medical devices. Each driver had TCP/IP connection code, initial processing code and updating data code.
We created common classes for each functionality as listed below, which segregated all the responsibilities required for driver development.
- TCPIOConnection
- DataReciever
- MessageExtrator
- UpdateData  
