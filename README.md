# Online-sales-inventory-management-system

This repository houses the frontend components of an inventory management system. The frontend is constructed using a robust combination of HTML, CSS, JavaScript, Bootstrap, and Tailwind CSS. 
**Inventory Management System for IoT Devices**

<h3>Table of Contents </h3>

* [Project Overview](https://www.google.com/url?sa=E&source=gmail&q=#project-overview)
* [Technologies Used](https://www.google.com/url?sa=E&source=gmail&q=#technologies-used)
* [System Architecture](https://www.google.com/url?sa=E&source=gmail&q=#system-architecture)
  * [Frontend](https://www.google.com/url?sa=E&source=gmail&q=#frontend)
  * [Backend](https://www.google.com/url?sa=E&source=gmail&q=#backend)
  * [Database](https://www.google.com/url?sa=E&source=gmail&q=#database)
  * [IoT Device Integration](https://www.google.com/url?sa=E&source=gmail&q=#iot-device-integration)
* [Installation and Setup](https://www.google.com/url?sa=E&source=gmail&q=#installation-and-setup)
  * [Prerequisites](https://www.google.com/url?sa=E&source=gmail&q=#prerequisites)
  * [Frontend Setup](https://www.google.com/url?sa=E&source=gmail&q=#frontend-setup)
  * [Backend Setup](https://www.google.com/url?sa=E&source=gmail&q=#backend-setup)
  * [Database Setup](https://www.google.com/url?sa=E&source=gmail&q=#database-setup)
  * [IoT Device Configuration](https://www.google.com/url?sa=E&source=gmail&q=#iot-device-configuration)
* [Usage Guide](https://www.google.com/url?sa=E&source=gmail&q=#usage-guide)
  * [Adding a New IoT Device](https://www.google.com/url?sa=E&source=gmail&q=#adding-a-new-iot-device)
  * [Viewing Inventory Data](https://www.google.com/url?sa=E&source=gmail&q=#viewing-inventory-data)
  * [Managing Stock Levels](https://www.google.com/url?sa=E&source=gmail&q=#managing-stock-levels)
  * [Generating Reports](https://www.google.com/url?sa=E&source=gmail&q=#generating-reports)
  * [Security Considerations](https://www.google.com/url?sa=E&source=gmail&q=#security-considerations)
* [Deployment (Optional)](https://www.google.com/url?sa=E&source=gmail&q=#deployment)
* [Contributing](https://www.google.com/url?sa=E&source=gmail&q=#contributing)
* [License](https://www.google.com/url?sa=E&source=gmail&q=#license)
* [Disclaimer](https://www.google.com/url?sa=E&source=gmail&q=#disclaimer)

<h3>Project Overview</h3>

This comprehensive inventory management system is specifically designed to streamline the tracking and management of IoT devices. It empowers you to:

* Maintain a centralized inventory of all your IoT devices with detailed information.
* Track real-time stock levels and receive alerts when they reach pre-defined thresholds.
* Generate insightful reports to gain valuable insights into your IoT inventory and optimize management strategies.

<h3>Technologies Used</h3>

* **Frontend:**
  * HTML: Provides the core structure of the web application.
  * CSS: Styles the user interface for a visually appealing and responsive presentation.
  * JavaScript (with a framework like React or Vue.js recommended): Enables dynamic interactions, data manipulation, and complex UI behavior.
  * Bootstrap (or Tailwind CSS): Offers pre-built UI components and utilities for a faster and more consistent development workflow.
* **Backend:**
  * PHP: Using a framework called Laravel for improved structure, maintainability, security, Handles server-side logic, data processing, and communication with the database.
* **Database:**
  * MySQL: Stores inventory data, device information, historical records, and other relevant data.
* **IoT Device Integration:**
  * Utilize appropriate communication protocols (e.g., MQTT, REST APIs) to establish secure and reliable connections with the IoT devices.

<h3>System Architecture</h3>

+-------------------+          +-------------------+          +---------------------+
|       Frontend     |          |       Backend       |          |       Database       |
+-------------------+          +-------------------+          +---------------------+
          |                    |                    |
          v                    v                    v
      (HTML, CSS, JS)      (PHP Framework, API Endpoints)        (MySQL)
          |                    |                    |
+-------------------+          +-------------------+          +---------------------+
| User Interface     |          | Data Processing    |          | Data Storage        |
+-------------------+          +-------------------+          +---------------------+
          |                    |                    |
          v                    v                    v
      (Inventory Views)      (Business Logic, Security)        (Device Information)
          |                    |                    |
+-------------------+          +-------------------+          +---------------------+
| User Interaction   |          | Real-time Updates  |          | Stock Levels         |
+-------------------+          +-------------------+          +---------------------+
          |                    |                    |
          v                    v                    v
      (Add/Edit Devices)      (Device Communication)        (Historical Data)
          |                    |                    |
+-------------------+          +-------------------+          +---------------------+
| Manage Inventory     |          | Reporting Engine   |          | Reports             |
+-------------------+          +-------------------+          +---------------------+

<h3>Functional Requirements</h3>

The user-friendly frontend provides a clear and intuitive interface for interacting with the system's features. Key functionalities include:

* **Inventory Dashboard:** Offers a visual overview of key inventory metrics, including real-time stock levels for different device types.
* **Search Items:** Explore available items, view product details, and search for specific items
* **Order Management:** (Sales Person,): Assist customers with order placement, process orders, and oversee overall sales operations
* **Signup/Login:** The system  allow users salespersons, customers, managers to sign up and log in securely using their credentials.
* **Payment:** The user/customer will be able to make payment using his card once he make order after it has been accepted by the inventory manager.
* **Make Order** Customers must be able to browse products, add them to the cart, Mandatory and make orders through the online platform.
* **Add User** Inventory manager must be able to add new users (e.g., salespersons, managers) to the system and assign appropriate roles and permissions.
* **View Order Items** The system must allow users to view the history of the items they order and the ones pending.
* Contributing

We welcome contributions to improve this inventory management system. Feel free to fork the repository, make changes, and submit pull requests.

<h3>License</h3>

This project is licensed under the MIT License.

Copyright (c) <b> Suhaib Muhammad Babangida </b>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

<h3>Disclaimer </h3>

This system is provided as-is, without any warranty. It may contain bugs or limitations. Feel free to fork the repository and customize it to your specific needs.
