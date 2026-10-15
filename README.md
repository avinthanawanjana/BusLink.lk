# BusLink.lk

**Repository Description:** 
BusLink.lk is a centralized web platform for Sri Lanka's private bus network, enabling owners to manage fleets and passengers to book seats, receive digital tickets, and track buses in real-time.

---

## About The Project
BusLink.lk is a web-based system built to organize and digitalize private bus services in Sri Lanka. The platform connects bus owners, drivers, conductors, passengers, and administrators to eliminate manual record-keeping and provide reliable, real-time transit information. 

## Key Features
* **Fleet & Route Management:** Bus owners have a centralized dashboard to register buses, assign staff, create routes with multiple stops, and update schedules.
* **Digital Booking & Ticketing:** Passengers can search for buses by route and time, book seats, and receive digital tickets equipped with verifiable QR codes.
* **Real-Time Map Tracking:** Utilizing the GPS on bus staff's mobile devices, passengers can track their assigned bus on an interactive map.
* **Location-Based Notifications:** The system calculates the distance to the pickup point and automatically alerts passengers when their bus is approaching.
* **Payment & Revenue Tracking:** Handles secure digital payments for passengers and generates revenue summaries and trip collection reports for bus owners.

## Technology Stack
* **Frontend:** React.js, Vite, and Tailwind CSS.
* **Backend:** Node.js, Express.js, and Socket.IO (for real-time updates).
* **Database:** MongoDB and Mongoose.
* **Security & Authentication:** JWT, bcrypt, and Role-Based Access Control.
* **Mapping & Geolocation:** Leaflet, OpenStreetMap, OSRM, and the browser Geolocation API.

## Architecture
BusLink.lk operates on a three-layer architecture. The React frontend communicates with the Node/Express backend via REST APIs and uses Socket.IO for live bidirectional data transfer, such as live bus location updates. The backend interfaces with MongoDB for structured data storage and external map APIs (OpenStreetMap and OSRM) for routing and distance calculations.
