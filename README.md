# GEOCAB - Taxi Services Application

GEOCAB is a robust, centralized database solution designed for taxi companies and transport organizations aiming to optimize their business processes, automate operations, and scale efficiently. The system provides real-time oversight of vehicle availability, dynamic trip pricing, and comprehensive management of drivers, clients, and financial transactions.

## Target Audience
The project is built for taxi companies that own and operate a fleet. The company acts as the database owner, requiring a streamlined system to manage its employees (drivers), assets (vehicles), and clients (passengers).

## Key Problems Solved
* **Manual Record Disruption:** Eliminates manual ride-logging by establishing a centralized digital ledger for all trip history.
* **Shift & Availability Control:** Offers precise tracking of driver shifts and real-time vehicle availability to improve dispatch efficiency.
* **Opaque Pricing:** Automates fare calculations based on pre-defined matrix structures, preventing inconsistencies.
* **Financial & Quality Feedback Loop:** Solves the challenge of tracking payment histories, customer complaints, and service ratings in one interconnected place.

## User Roles (Actors)
* **Administrators:** Company backend staff who oversee all operations, manage vehicle inventory, define tariff models, and monitor overall performance.
* **Drivers:** Frontline service providers who view their assigned shifts, active vehicle statuses, and completed trips.
* **Clients (Passengers):** End-users who create accounts, request transport services, track their ride history, and rate the quality of service.

## What Makes GEOCAB Different? (Key Advantages)
Unlike rigid out-of-the-box software, GEOCAB features a highly adaptable, **data-driven dynamic pricing model** embedded directly within the database architecture. 
* **Configurable Tariffs:** Base fares are explicitly mapped out across various vehicle classes (Standard, Luxury, Van) and scale progressively per kilometer.
* **Zero-Code Adjustments:** Fleet managers can change pricing structures, add vehicle categories, or update surge rates instantly via database updates without rewriting a single line of application code, ensuring high market adaptability.

## Application Type & Tech Stack
* **Architecture:** Formulated as a scalable Web Application accessible via any standard web browser.
* **Core Technology:** PostgreSQL / DataGrip (Relational Database Design)
* **Core Modules:** Spatial Location Processing, Dynamic Tariffs, Shift Scheduling, Rating & Ledger Management.

---

## Future Database Optimization Plans
* Implementing advanced spatial indexes for faster geographic location queries.
* Partitioning heavy transaction ledger tables to handle long-term history scaling.
