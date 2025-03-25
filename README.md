# OnlineFoodDelivery-Service
Khuda Lagse - Online Food Delivery System  A Java Swing/FX and MySQL-based food delivery platform connecting customers with local restaurants. Features user authentication, menu browsing, order placement, admin dashboard, and PDF billing.


Here it is an Java based project. In 2nd year 1st semester in OODP-II course I made this project with my classmates. 

The Details description has giveen below of the project:

 Project Overview:
"Khuda Lagse" is an online platform aimed at connecting customers with local restaurants and food vendors, providing them with a convenient and user-friendly way to order food and get it delivered to their doorsteps. This application is built using Java Swing/FX for the graphical user interface and MySQL for managing the back-end database.

 Project Objectives:

The main objectives of the "Khuda Lagse" project are:

 To create an intuitive and easy-to-use interface for customers to browse menus, place orders, and make payments.
 To provide restaurant vendors with a platform to showcase their menu, receive orders, and manage transactions.
 To ensure secure and efficient handling of customer data and transaction details.
 To facilitate updates on order status for both customers and vendors.

 System Architecture:
The "Khuda Lagse" application follows a client-server architecture:
 Client Side (Java Swing/FX): This is the user interface through which customers interact with the service. It includes features like user registration, login, menu browsing and order placement.
 Server Side (MySQL Database): This stores all the necessary data including user information, restaurant details, menu items, and order status.

 Technologies Used:
 Java Swing/FX: Used for creating the graphical user interface of the application.
 MySQL: Used for storing and managing all the data related to users, restaurants, orders, and transactions.
 Java JDBC: Used for connecting the Java application with the MySQL database.
 Functionalities and Features:
 Customer Side: User Registration and Login: Allows new users to register and existing users to log in.
 Browse Menus: Customers can browse through various restaurant menus and select items to add to their cart.
 Place Orders: Customers can place orders, view the total cost, and make payment.

 Key Features:

 Add New Product:

Within the "Add New Product" section, the administrator has the capability to include fresh products, specifying both the product name and its corresponding price within a designated category.
 Change Password:
Both the user and the administrator have the option to reset their passwords by answering their respective security questions.

 Manage Category:
In the "Manage Category" section, the administrator can introduce new food categories into the category table, and subsequently, these categories are stored in the database for future use.

 Total Revenue:
Under Total Revenue, the admin can see all the money generated from the orders placed by the users including the total list of orders stage.

 Place Order:
In the "Place Order" section, users can select food items to place an order. Each time they click on a food item, an image of the selected food will appear. Users have the flexibility to adjust the quantity of the selected items. However, the final bill will not be generated unless they provide their name and phone number. Once these details are provided, a PDF of the bill will be generated at a later stage.

 Verify Users:
In the Verify Users section, admins can verify new user accounts to allow access to the application's features, and disable existing user accounts.

 View Bills Order History:
In the View Bills Order History section, admins can view a table of all orders placed by users, including the user's name, email address, total amount, phone number, and date. Admins can also filter the table by date or search by user name. Additionally, admins can sort the table in ascending or descending order by any column.

 View Order History:
Under View, Edit, and Delete Products, admins can view a list of all products in their respective categories, including the product name, price, and product ID. Admins can also edit the product name, price, and category.
Under View Order History, users can view a list of all orders they have placed in the app, including the order name, total amount, order ID, phone number, email, order date, total payment, and created by. Users can also click on an order to view a PDF of the bill.

 Slide Show of the Food Items:
The food items will be displayed in a slideshow that slowly shuffles. Users can close the slideshow at any time, or click on the button to display it again.

 Restaurant Vendor/Admin Side:
 Manage Menu: Allows vendors to add, remove, or update menu items.
 Receive Orders: Vendors can view incoming orders, update order status, and manage transactions.
 View Transaction History: Vendors can view past transactions and order histories.

 Database Design:
The MySQL database includes the following tables:
 Users: Stores customer and vendor details.
 Restaurants: Stores restaurant details.
 Menu Items: Stores menu details for each restaurant.
 Orders: Stores details of customer orders.
 Transactions: Stores transaction details for each order.

 Challenges and Solutions:
 Security: Ensuring secure handling of user data and transaction details. This was mitigated by implementing encryption and secure connection protocols.
 Real-Time Updates: Ensuring that order status is updated in real-time for both customers and vendors. This was achieved using event-driven programming and database triggers.

 Future Enhancements:
 Mobile Application: Developing a mobile app version of the service.
 Enhanced User Interface: Further improvements to the user interface for a more seamless experience.
 Expansion of Services: Expanding the service to cover more areas and include more restaurant options.

 Conclusion:
"Khuda Lagse" aims to provide a seamless and efficient online food ordering experience, connecting customers with a variety of local restaurants. By Java Swing/FX and MySQL, the application offers a robust and user-friendly platform for food delivery services. The system is well-equipped to handle customer orders and assist restaurant owners in managing their business operations. With the ever-increasing demand for such services, this project holds significant potential for expansion and growth.
