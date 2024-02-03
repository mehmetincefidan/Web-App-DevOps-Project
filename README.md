# Web-App-DevOps-Project

Welcome to the Web App DevOps Project repo! This application allows you to efficiently manage and track orders for a potential business. It provides an intuitive user interface for viewing existing orders and adding new ones.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Technology Stack](#technology-stack)
- [Contributors](#contributors)
- [License](#license)

## Features

- **Order List:** View a comprehensive list of orders including details like date UUID, user ID, card number, store code, product code, product quantity, order date, and shipping date.
  
![Screenshot 2023-08-31 at 15 48 48](https://github.com/maya-a-iuga/Web-App-DevOps-Project/assets/104773240/3a3bae88-9224-4755-bf62-567beb7bf692)

- **Pagination:** Easily navigate through multiple pages of orders using the built-in pagination feature.
  
![Screenshot 2023-08-31 at 15 49 08](https://github.com/maya-a-iuga/Web-App-DevOps-Project/assets/104773240/d92a045d-b568-4695-b2b9-986874b4ed5a)

- **Add New Order:** Fill out a user-friendly form to add new orders to the system with necessary information.
  
![Screenshot 2023-08-31 at 15 49 26](https://github.com/maya-a-iuga/Web-App-DevOps-Project/assets/104773240/83236d79-6212-4fc3-afa3-3cee88354b1a)

- **Data Validation:** Ensure data accuracy and completeness with required fields, date restrictions, and card number validation.

## Getting Started

### Prerequisites

For the application to succesfully run, you need to install the following packages:

- flask (version 2.2.2)
- pyodbc (version 4.0.39)
- SQLAlchemy (version 2.0.21)
- werkzeug (version 2.2.3)

### Usage

To run the application, you simply need to run the `app.py` script in this repository. Once the application starts you should be able to access it locally at `http://127.0.0.1:5000`. Here you will be meet with the following two pages:

1. **Order List Page:** Navigate to the "Order List" page to view all existing orders. Use the pagination controls to navigate between pages.

2. **Add New Order Page:** Click on the "Add New Order" tab to access the order form. Complete all required fields and ensure that your entries meet the specified criteria.

## Technology Stack

- **Backend:** Flask is used to build the backend of the application, handling routing, data processing, and interactions with the database.

- **Frontend:** The user interface is designed using HTML, CSS, and JavaScript to ensure a smooth and intuitive user experience.

- **Database:** The application employs an Azure SQL Database as its database system to store order-related data.

## Contributors 

- [Maya Iuga]([https://github.com/yourusername](https://github.com/maya-a-iuga))

## License

This project is licensed under the MIT License. For more details, refer to the [LICENSE](LICENSE) file.


Feature Documentation: Delivery Date Feature
Table of Contents
Introduction
Feature Overview
How It Works
Backend Changes
Frontend Integration
Usage Guide
For Developers
For End-Users
Reverting Changes
Future Considerations
Troubleshooting
Version History
Contributing
Contact Information
Introduction
This documentation provides an overview and detailed information about the Delivery Date feature in the company's internal application. It is aimed at both developers and end-users, providing insights into the functionality and usage of the feature.

Feature Overview
The Delivery Date feature allows users to track and manage the expected delivery dates of items within the application. It was designed to enhance the overall user experience by providing accurate delivery information.

How It Works
Backend Changes
The feature involves modifications to the backend Azure SQL Database, specifically the addition of the delivery_date column. This column is intended to store the expected delivery dates associated with each item.

Frontend Integration
The frontend of the application integrates with the backend changes to display the delivery date information to end-users. User interfaces have been updated to accommodate the new feature seamlessly.

Usage Guide
For Developers
Developers can utilize the Delivery Date feature by accessing the delivery_date column in the backend database. Ensure that the necessary API endpoints and data models are updated to support the feature. For detailed information on implementation, refer to the code changes made in the commit history.

For End-Users
End-users can view and manage delivery dates within the application's user interface. Look for the "Delivery Date" section when interacting with items, and follow on-screen prompts to set or update delivery dates.

Reverting Changes
In case a decision is made to revert the feature, follow the documented steps in the Reverting Changes section. This will guide you through the process of undoing the modifications made to the codebase.

Future Considerations
While the feature has been reverted, there might be future considerations for its reintroduction. Developers are encouraged to review the feature's implementation and consider potential enhancements or modifications if it is reintroduced in subsequent releases.

Troubleshooting
Refer to the Troubleshooting section for common issues and solutions related to the Delivery Date feature.

Version History
Version 1.0.0 (Initial Release)
Added: delivery_date column to the backend database.
Integrated: Frontend changes to display and manage delivery dates.
Contributing
If you have suggestions, improvements, or bug reports, please contribute to the project by submitting issues or pull requests.

Contact Information
For further assistance or inquiries, please contact the development team at development-team@example.com.

Feel free to tailor the content to fit the specifics of your feature and application. This template provides a structured approach to delivering comprehensive documentation.
