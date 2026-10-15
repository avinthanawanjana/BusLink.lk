# BusLink.lk

**Repository Description:** 
BusLink.lk is a centralized web platform for Sri Lanka's private bus network, enabling owners to manage fleets and passengers to book seats, receive digital tickets, and track buses in real-time[cite: 2, 3].

---

## About The Project
BusLink.lk is a web-based system built to organize and digitalize private bus services in Sri Lanka[cite: 2]. The platform connects bus owners, drivers, conductors, passengers, and administrators to eliminate manual record-keeping and provide reliable, real-time transit information[cite: 2]. 

## Key Features
* **Fleet & Route Management:** Bus owners have a centralized dashboard to register buses, assign staff, create routes with multiple stops, and update schedules[cite: 3, 8].
* **Digital Booking & Ticketing:** Passengers can search for buses by route and time, book seats, and receive digital tickets equipped with verifiable QR codes[cite: 3, 8].
* **Real-Time Map Tracking:** Utilizing the GPS on bus staff's mobile devices, passengers can track their assigned bus on an interactive map[cite: 3, 9].
* **Location-Based Notifications:** The system calculates the distance to the pickup point and automatically alerts passengers when their bus is approaching[cite: 3, 9].
* **Payment & Revenue Tracking:** Handles secure digital payments for passengers and generates revenue summaries and trip collection reports for bus owners[cite: 4, 9].

## Technology Stack
* **Frontend:** React.js, Vite, and Tailwind CSS[cite: 5].
* **Backend:** Node.js, Express.js, and Socket.IO (for real-time updates)[cite: 5].
* **Database:** MongoDB and Mongoose[cite: 5].
* **Security & Authentication:** JWT, bcrypt, and Role-Based Access Control[cite: 5].
* **Mapping & Geolocation:** Leaflet, OpenStreetMap, OSRM, and the browser Geolocation API[cite: 5].

## Architecture
BusLink.lk operates on a three-layer architecture[cite: 10]. The React frontend communicates with the Node/Express backend via REST APIs and uses Socket.IO for live bidirectional data transfer, such as live bus location updates[cite: 10]. The backend interfaces with MongoDB for structured data storage and external map APIs (OpenStreetMap and OSRM) for routing and distance calculations[cite: 10].
