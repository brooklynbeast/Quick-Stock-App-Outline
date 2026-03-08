# Quick Stock – Android App Project Final Outline  
COM-437 Mobile Application Development  
Saint Leo University  

## I. Project Description

### Application Name  
Quick Stock

### Overview  
Quick Stock is an Android-based inventory spot check application designed for fast-paced work environments. The purpose of the application is to simplify quick inventory updates during busy shifts where employees often do not have time to perform full inventory counts.

The application allows users to quickly update item quantities, identify low-stock products, and view alerts without navigating complicated systems. The design focuses on speed, simplicity, and one-handed usability so employees can perform spot checks while working.

The goal of the project is to demonstrate a functional Android prototype that shows how mobile applications can improve efficiency in real work environments.

### Target Users  
- Retail employees  
- Shift supervisors  
- Store managers  
- Warehouse staff  
- Commissary employees  

### Term Goals  
- Develop a functional Android prototype using Android Studio  
- Implement a login authentication screen  
- Create an inventory spot check interface  
- Implement a low stock alert system  
- Store inventory updates in a local database  
- Demonstrate functional user interface navigation  
- Design clear wireframes showing application workflow  

## II. Problem Addressing

### Current Problem  
Many workplaces rely on manual or informal inventory tracking methods. Employees often write down inventory levels on paper or rely on memory during busy shifts. Because of this, inventory shortages are often discovered too late.

Common issues include:  
- Inventory shortages discovered after items run out  
- Employees wasting time searching for missing items  
- Managers lacking real-time visibility of stock levels  
- Errors caused by manual tracking  

These inefficiencies can negatively affect both employees and customers.

### Why This Matters  
Inventory visibility is important because it directly impacts:  
- Customer satisfaction  
- Employee productivity  
- Store operations  
- Supply management  

When items run out unexpectedly, it creates delays, frustration, and lost revenue.

### Proposed Solution  
Quick Stock solves this problem by providing a simple tap-based system that allows employees to update inventory quickly during their shifts.

The application automatically detects when stock levels fall below a defined threshold and displays a low stock alert to the user.

By digitizing spot checks, the application improves:  
- Speed of inventory updates  
- Accuracy of information  
- Visibility of stock shortages  
- Overall operational efficiency  

## III. Platform

The Quick Stock application was developed for the Android platform.

### Development Tools and Technologies  
- **Platform:** Android Operating System  
- **Development Environment:** Android Studio  
- **SDK:** Android Software Development Kit (SDK)  
- **Minimum Android Version:** Android 10+  
- **Testing:** Android Emulator and physical device testing  
- **Connectivity:** Offline-first design using a local database. Future versions may support cloud synchronization.  

## IV. Front-End and Back-End Support

### Front-End Interface  
The application contains several user interface screens designed to simplify navigation and improve usability.

#### Primary Screens  
- **Login Screen** – Allows employees to enter credentials to access the system  
- **Dashboard Screen** – Displays main application functions and provides navigation to inventory features  
- **Spot Check Screen** – Allows users to enter and update item quantities quickly  
- **Low Stock Alert Screen** – Displays items that are low in inventory and require attention  
- **Settings Screen** – Allows configuration options for the application  

#### Navigation  
A bottom navigation bar may include:  
- Home  
- Check  
- Alerts  
- History  

This design improves speed and reduces the number of taps required during busy shifts.

### Back-End Support  
The application uses a local database to store inventory updates and track item changes.

#### Database Technology  
- SQLite or Room Database  

#### Stored Data Includes  
- Item name  
- Quantity level  
- Timestamp of update  
- Alert status  

This allows the application to operate even without an internet connection.

### Security  
Basic authentication is implemented to protect access to the application.

#### Security Features  
- Employee login authentication  
- Local data storage protection  
- Controlled access to inventory updates  

## V. Functionality

### Core Features  
The Quick Stock application includes the following main features:  
- Employee login authentication  
- Start or stop inventory spot checks  
- Quantity input fields for inventory items  
- Automatic low stock detection  
- Color indicators for inventory status  
- Critical stock indicator (Red)  
- Low stock indicator (Yellow)  
- Submit inventory update button  
- Mark alerts as reviewed  
- Display last updated timestamps  

### Secondary Features  
Additional features designed for usability include:  
- Inventory categories  
- Application settings  
- Historical tracking of spot checks  
- Navigation shortcuts  

These features support efficient workflow during busy shifts.

## VI. Design (Wireframes)

### Wireframe Development  
The application wireframes were initially created using hand-drawn sketches to quickly visualize the layout and workflow.

These sketches were later recreated digitally to improve clarity and presentation.

The design goal was to minimize the number of taps required to complete a spot check.

### Screen Layouts

#### Login Screen  
Displays the application title and login form.

**Components include:**  
- App title (Quick Stock)  
- Employee ID input field  
- Password input field  
- Login button  

#### Dashboard Screen  
Provides access to the main application features.

**Components include:**  
- Start Spot Check button  
- View Alerts button  
- Inventory Categories  
- Settings menu  
- Last updated timestamp  

#### Spot Check Screen  
Allows users to update inventory quickly.

**Example items displayed may include:**  
- Milk  
- Bread  
- Cleaning supplies  

**Components include:**  
- Item list  
- Quantity input fields  
- Low stock indicators  
- Submit update button  

#### Low Stock Alert Screen  
Displays items that require attention.

**Components include:**  
- Inventory status list  
- Red indicator for critical items  
- Yellow indicator for low items  
- Mark as reviewed button  

## VII. Future Enhancements

Future versions of the Quick Stock application may include additional functionality such as:  
- Barcode scanning for faster inventory entry  
- Cloud database synchronization  
- Role-based access (manager vs employee)  
- Inventory analytics dashboard  
- Reporting features for managers  

These enhancements would improve scalability and support larger business operations.

## VIII. Project Status

Current development progress includes:  
- Wireframes completed  
- Application concept defined  
- Documentation finalized  
- GitHub repository created  
- README documentation updated  

The project demonstrates the design and planning process required for mobile application development.

## Version Changelog

### Version 1.0 – Initial Outline Submission  
- Defined project concept and business problem  
- Selected Android development platform and tools  
- Created initial wireframes and workflow structure  

### Version 2.0 – Module 5 Update  
- Refined navigation structure and user interface layout  
- Expanded low stock alert functionality  
- Improved project documentation  

### Version 3.0 – Final Submission  
- Finalized project outline and documentation  
- Updated GitHub README file  
- Prepared final report and presentation materials  
