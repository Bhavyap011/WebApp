# Maintenance Request System

## Overview

The **Maintenance Request System** is a web-based application designed to streamline the management of maintenance requests within an apartment building. The system is divided into three sections:

- **Tenant Section**: Allows tenants to submit maintenance requests with details such as the apartment number, problem area, and description.
- **Staff Section**: Lets staff members filter and view maintenance requests, and take action by changing their status.
- **Manager Section**: Provides tools for managers to manage tenant information, including adding new tenants, moving tenants between apartments, or deleting tenant records.

The system integrates with Firebase Firestore to store and retrieve data, ensuring real-time updates and efficient data management.

## Features

- **Tenant Section**: 
  - Submit maintenance requests with details like apartment number, problem area, and description.
  
- **Staff Section**: 
  - Filter maintenance requests by apartment number, area, date range, and status.
  - View and update the status of maintenance requests.

- **Manager Section**: 
  - Add, move, or delete tenants.
  - View a list of all tenants with detailed information such as name, phone number, check-in/check-out dates, and apartment numbers.

## Installation

To run the system locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/maintenance-request-system.git
    ```

2. **Set up Firebase**:
    - You will need a Firebase account. Go to [Firebase Console](https://console.firebase.google.com/) to create a project.
    - Replace the Firebase configuration in the `script` section of the HTML file with your own credentials (found in your Firebase project's settings).

3. **Open the project in your browser**:
    - Simply open the `index.html` file in your browser to view and interact with the application.

## Technologies Used

- **HTML/CSS**: For the basic structure and styling of the web pages.
- **JavaScript**: For handling user interactions and logic, including communication with Firebase.
- **Firebase Firestore**: Used for storing maintenance requests and tenant data in real-time.



