RestaurantMan Backend API
=========================

My contributions: I was in charge of making the backend api. I designed a mySQL database to hold all app data, with AWS S3 for image hosting. I created a node.js api server using express.js. I also handled user authentication and authorization through JWT tokens. Set up AWS environment for these services: S3, EC2, Elastic Beanstalk, Elastic Load Balancer, CloudFront, AWS RDS, R53, IAM, CloudFormation, CodeStar.  

Frontend code: https://github.com/BryanC21/RestaurantMan-frontend

University Name: http://www.sjsu.edu/  
Course: Cloud Technologies http://info.sjsu.edu/web-dbgen/catalog/courses/CMPE281.html   
Professor Sanjay Garje https://www.linkedin.com/in/sanjaygarje/   
Students: Bryan Caldera https://www.linkedin.com/in/bryan-caldera-50a97b187/ , Hongru Lin https://www.linkedin.com/in/hongrulin/ , Murali Monish https://www.linkedin.com/in/murali-monish/ 

Project Introduction
===================

RestaurantMan is a website designed for restaurant management where, Customers can register a user account to place orders in-store or pick up. Restaurant owners can register and manage orders and tables, while storing all the data in the cloud for further analysis. This would be marketed as a SaaS (Software as a Service) program for brick and mortar restaurants looking for a more personalized in-house experience for its customers.  

Feature List
============
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

Restaurant owners are able to register for the app and manage their restaurant and food menu:  
<img width="424" alt="Screenshot 2023-04-02 at 10 30 05 AM" src="https://user-images.githubusercontent.com/32147608/229369145-7af3e6be-99dc-4ada-8c41-696f30bcea73.png">

<img width="496" alt="Screenshot 2023-04-02 at 10 31 24 AM" src="https://user-images.githubusercontent.com/32147608/229369170-d1577b81-76fb-4574-81c9-44d623da6635.png">

Users can place orders for restaurants:  
<img width="468" alt="image" src="https://user-images.githubusercontent.com/32147608/229369192-dab4d315-b553-42fe-9d55-5897fa2d0907.png">

<img width="468" alt="image" src="https://user-images.githubusercontent.com/32147608/229369205-cc890235-c5eb-461e-be59-224764963d71.png">

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
