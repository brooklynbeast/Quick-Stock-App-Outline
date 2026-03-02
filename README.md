# Quick Stock – Android App Project Outline
Module 2 – Android App Development

---

## I. Project Description

### Application Name
Quick Stock

### Overview
Quick Stock is an Android-based inventory spot check application designed for fast-paced work environments. The purpose of this app is to simplify quick inventory updates during busy shifts. Employees will be able to update item quantities, identify low stock items, and view alerts without navigating complex systems. The design focuses on speed, simplicity, and one-handed usability.

### Target Users
- Retail employees
- Shift supervisors
- Store managers
- Warehouse staff

### Term Goals
- Develop a working Android prototype
- Implement login functionality
- Create inventory spot check screen
- Implement low stock alert system
- Store updates in a local database
- Demonstrate functional UI navigation

---

## II. Problem Addressing

### Current Problem
In many work environments, inventory shortages are discovered too late. Spot checks are often written on paper or tracked informally. This causes delays, errors, and inefficiencies.

### Why This Matters
- Customers experience out-of-stock items
- Employees waste time searching for products
- Managers lack real-time visibility
- Operational efficiency decreases

### Proposed Solution
Quick Stock provides a fast tap-based system for updating inventory. The app automatically detects low stock levels and highlights critical items. This reduces time spent performing spot checks and improves accuracy.

---

## III. Platform

- Platform: Android Operating System
- Development Environment: Android Studio
- SDK: Android SDK
- Testing: Emulator and physical device
- Minimum Version: Android 10+
- Connectivity: Designed to function offline (future cloud integration possible)

---

## IV. Front-End and Back-End Support

### Front-End Screens
- Login Screen (Employee ID and Password)
- Dashboard Screen
- Spot Check Screen
- Low Stock Alert Screen
- Settings Screen
- Optional Bottom Navigation (Home, Check, Alerts, History)

### Back-End Support
- Local database using SQLite or Room
- Stores item name, quantity, timestamp, and alert status
- Tracks last updated time

### Security
- Basic employee authentication
- Local data storage protection

---

## V. Functionality

### Core Features
- Employee login authentication
- Start/Stop inventory spot check
- Quantity input fields
- Automatic low stock detection
- Critical stock indicator (Red)
- Low stock indicator (Yellow)
- Submit update button
- Mark alerts as reviewed
- Display last updated timestamp

### Secondary Features
- Inventory categories
- Settings configuration
- Historical tracking of checks
- Bottom navigation for faster access

---

## VI. Design (Wireframes)

### Wireframe Process
The initial wireframes were created using pen and paper to focus on layout and flow. The design was then recreated digitally for alignment and clarity. The goal was to minimize the number of taps required to complete a spot check.

### Screen Breakdown

#### Login Screen
- App Title: Quick Stock
- Employee ID input
- Password input
- Log In button

#### Dashboard Screen
- Start Spot Check
- View Alerts
- Inventory Categories
- Settings
- Last Updated display

#### Spot Check Screen
- Item list (Milk, Bread, Cleaning Supplies)
- Quantity input fields
- Low stock indicator
- Submit Update button

#### Low Stock Alert Screen
- Item status list
- Red indicator for critical items
- Yellow indicator for low items
- Mark as Reviewed button

### Alternative Navigation
A bottom navigation bar (Home, Check, Alerts, History) may improve usability by reducing extra steps and increasing speed during busy shifts.

---

## VII. Future Enhancements
- Barcode scanning integration
- Cloud database synchronization
- Role-based access (Manager vs Employee)
- Analytics dashboard for inventory trends

---

## Project Status
Wireframes completed.
Initial documentation complete.
Repository created for project development.<img width="843" height="1767" alt="5" src="https://github.com/user-attachments/assets/abb761cb-a56c-4d85-a81f-3faf5033d987" />
<img width="843" height="1767" alt="4" src="https://github.com/user-attachments/assets/06212eb1-afae-474a-b2e1-9a2ba1ddd4ad" />
<img width="843" height="1767" alt="3" src="https://github.com/user-attachments/assets/c8f01a3d-e53b-4a6c-9370-724fbd383794" />
<img width="843" height="1767" alt="2" src="https://github.com/user-attachments/assets/da4e24f4-d2c5-4f9b-bb45-b198c242f039" />
<img width="843" height="1767" alt="1" src="https://github.com/user-attachments/assets/8ba2808c-fc6a-4b30-a917-49dcd450eaba" />
Version Changelog

Version 1.0 – Initial Outline Submission
Defined project concept and identified business problem
Selected Android development platform and tools
Created initial wireframes and workflow structure

Version 2.0 – Module 5 Update
Refined navigation structure and user interface layout
Expanded low stock alert functionality planning
Improved project documentation and README clarity
Aligned GitHub repository and Wiki with updated outline
