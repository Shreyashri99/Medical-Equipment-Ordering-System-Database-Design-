# Medical-Equipment-Ordering-System-Database-Design

# Overview

This document provides an overview of the "Medical Equipment Ordering System" project, outlining its objectives, design, implementation, and future scope. The report details the development of a web-based platform for streamlining medical equipment procurement, integrating database management, user authentication, and analytics capabilities.

# Project Details

Title: Medical Equipment Ordering System

Institution: Khoury College of Computer Sciences, Northeastern University

Keywords: Flask, Web Application, User Authentication, Order Processing, Analytics Dashboard, SQL Stored Procedures, Triggers, Functions, SQL Views

# Purpose

The project aims to enhance the medical equipment procurement process by providing an efficient, user-friendly system for healthcare facilities, suppliers, and customers. It centralizes ordering, tracking, and management of medical equipment while ensuring data accuracy and accessibility.

# System Features

User Registration & Authentication: Secure login and account management for customers.

Order Management: Place, update, and delete orders seamlessly.

Inventory Management: Tracks equipment stock across suppliers.

Supplier & Customer Classification: Organized by business type, specialty, and location.

Analytics Dashboard: Provides insights into best-selling products, average sales by state and date, and supplier availability.

Technology Stack

Database: MySQL

Front-End: HTML, CSS, AJAX

Back-End: Python Flask

Data Processing: Pandas, SQL Queries

Dashboarding: Plotly, Dash

# Data Collection

Data sourced from Centers for Medicare & Medicaid Services (CMS)

Data cleaning, normalization, and integration processes were implemented using Python and SQL.

# Database Design

Entity-Relationship Diagram (ERD) comprising tables for Suppliers, Customers, Orders, Equipment, and Location.

Normalization: Ensured adherence to 1NF, 2NF, and 3NF to maintain data integrity and minimize redundancy.

Stored Procedures & Triggers: Used for order processing, stock updates, and analytics calculations.

# Application Workflow

Customer Registration: Users provide details including name, address, and login credentials.

Login & Authentication: Secure validation of email and password using hashed encryption.

Dashboard Access: Customers can browse equipment, place orders, and view past transactions.

Order Processing: Customers can select suppliers, adjust quantities, and track order history.

Analytics & Reporting: The system generates insights on supplier performance and sales trends.

# Future Enhancements

Integration of Machine Learning Models: Predictive analytics for demand forecasting.

Mobile Optimization: Improved accessibility across devices.

Personalized Alerts: Notifications for new equipment availability and price changes.

Integration with External Healthcare Systems: Seamless interoperability with existing platforms.

Conclusion

This project has provided valuable insights into database management, UI/UX design, security implementation, and agile development. The system offers a structured and scalable solution for medical equipment procurement, addressing key challenges in supplier-customer interactions.

