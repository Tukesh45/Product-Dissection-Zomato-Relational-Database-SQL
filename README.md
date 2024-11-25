# Zomato Database and Schema Project
# Overview
This project is a database schema for a Zomato-like food delivery platform, designed to manage users, restaurants, menus, orders, reviews, delivery partners, and routes. The schema is implemented in SQL and includes an Entity-Relationship (ER) diagram for clear visualization of the relationships among entities.

The purpose of this project is to showcase a robust and scalable relational database design for a food delivery and restaurant review platform.

# Features
1. User Management
Register users with personal details, including email and phone verification.
Maintain profiles for account personalization.

2. Restaurant and Menu Management
Add and manage restaurant details, including cuisines, ratings, and contact information.
Maintain menus with item details like price and category.

3. Order Tracking
Track food orders with order statuses and total price.
Associate users with their placed orders and restaurants with fulfilled orders.

4. Reviews and Ratings
Users can leave reviews and ratings for restaurants to share their dining experiences.

5. Delivery Management
Assign delivery partners to orders and track real-time delivery routes.

6. Scalable Relationships
Design supports many-to-many relationships (e.g., reviews, orders, and menus) and includes primary and foreign keys for referential integrity.

# Entity-Relationship Diagram
Below is the ER Diagram that illustrates the relationships and attributes of the database schema:
The database schema consists of the following entities:

1. Users: Manages user accounts and profiles.
2. Restaurants: Stores information about restaurants.
3. Menus: Represents food items offered by restaurants.
4. Orders: Tracks orders placed by users.
5. Reviews: Contains user feedback and ratings for restaurants.
6. DeliveryPartners: Manages delivery personnel information.
7. DeliveryRoutes: Tracks delivery logistics.
   
# Database Schema
The database schema is implemented in SQL and includes the following tables:
1. Users
2. Restaurants
3. Menus
4. Orders
5. Reviews
6. DeliveryPartners
7. DeliveryRoutes
Each table is designed with primary and foreign keys to ensure data integrity and maintain relationships.
