# ElectroCharge Pro: Intelligent EV Charging Station Locator and Reservation

## Abstract
ElectroCharge Pro simplifies booking and managing EV charging stations. Developed in Java using JavaFX, the MVC framework, data structures, and MySQL, this desktop application enables users to locate and reserve charging stations in advance by entering their source and destination locations.

## Introduction
The rise in electric vehicles (EVs) necessitates robust charging infrastructure. This project aims to mitigate range anxiety by providing real-time data on charging station locations, availability, and booking options.


## Problem Statement
Despite the rise in EV adoption, the lack of dependable infrastructure for finding and accessing charging stations remains a barrier. ElectroCharge Pro addresses this by offering queue management, availability information, and efficient trip planning.

## Objectives
- Develop a user-friendly interface for booking EV charging stations.
- Implement real-time status updates.
- Integrate secure user registration and authentication.
- Efficiently store and retrieve data using MySQL.
- Apply the MVC architectural pattern for maintainable code.

## Methodology

### Project Architecture
- *MVC Framework*:
  - *Model*: Business logic and data processing, including MySQL database interaction.
  - *View*: User interface developed using JavaFX.
  - *Controller*: Handles user input, processes requests, and updates the View.

### Database Integration
MySQL stores information about EV stations, user accounts, and bookings. JDBC is used for database operations.

### Data Structure and Algorithm
- *Data Structure*:
  - Java Collections (ArrayLists) store state, city, and address data for ComboBoxes.
- *Algorithm*:
  - The MVC pattern separates application components to improve organization and scalability.

