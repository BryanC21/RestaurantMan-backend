RestaurantMan Backend API
=========================

CHECK API-DOCUMENTATION.md FOR MORE DETAILS ON ROUTES

University Name: http://www.sjsu.edu/  
Course: Cloud Technologies http://info.sjsu.edu/web-dbgen/catalog/courses/CMPE281.html   
Professor Sanjay Garje https://www.linkedin.com/in/sanjaygarje/   
Students: Bryan Caldera, Hongru Lin, Murali Monish

Project Introduction
===================
This project is inspired by going to restaurants where they are very busy and don’t have enough waiters to serve every table which makes the efficiency low. Having a website that can allow people to view menus and order through the website can increase the restaurants’ efficiency and reduce the cost of manpower. Also, it would be very easy to manage the restaurant even on your phone. Updating menus becomes very easy and free. 
This website will be very helpful for every restaurant owner who is experiencing difficulty in managing orders, seeking better efficiency, saving costs, or loves exploring new menus.
RestaurantMan is a website designed for restaurant management where, Customers can register a user account to place orders in-store or pick up. Restaurant owners can register and manage orders and tables, while storing all the data in the cloud for further analysis. This would be marketed as a SaaS (Software as a Service) program for brick and mortar restaurants looking for a more personalized in-house experience for its customers.  

Feature List
============
SSO
Register
Login
Logout
Admin:
Menu
Add Item
Update Item
Remove Item
Orders
Update Order
Complete Order
Cancel Order
Tables
Add Table
Update Table
Remove Table
Generate QR code for customers
Analysis
View restaurant revenues and sales in graph
Customer:
Menu
Scan QR code in the store
View Items
Play sound for item name
Order
Add item to cart
Update item
Remove item
Place Order
Summary
View previous orders



Sample Demo Screenshots
===================
IN PROJECT SUBMISSION DOC

Pre-requisites Set Up
===================
AWS: S3, EC2, Elastic Beanstalk, Elastic Load Balancer, Lambda, API, CloudFront, AWS RDS, R53, IAM, CloudFormation, CodeStar

List of required software to download locally
===================
* NodeJS
* NPM

Local configuration
How to set up and run project locally?
Backend API 
===================
To run:  
0. Clone this repo
1. Install dependencies: `npm install`
2. Build the database: `node db_builder.js drop` //step can be skipped if databse is built already
3. Run the server: `node server.js`