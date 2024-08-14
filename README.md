# FinalSprint-BinarySearchTree

Binary Search Tree Visualization

#Overview
The Binary Search Tree Visualization project provides a web-based tool to create, visualize, and store binary search trees (BST). Users can input a series of numbers to construct a BST, view the tree structure in JSON format, and access previously stored trees. This project is built using Spring Boot and Thymeleaf for the web interface, with MySQL as the database for storing user inputs and tree structures.

#Features
Interactive Tree Creation: Users can enter a series of numbers to dynamically create a binary search tree.
JSON Representation: The tree structure is displayed in JSON format, making it easy to visualize and understand the hierarchy.
History Tracking: View previously created trees with their respective input numbers and JSON structures.
User Management: Store user inputs and tree structures in a MySQL database.

#Getting Started and Installation

Prerequisites
Java 11 or higher
Maven
MySQL Database
Spring Boot

#Setup
1. Clone the Repository:
   git clone https://github.com/JohnLimon/FinalSprint-BinarySearchTree.git
   cd FinalSprint-BinarySearchTree
2. Configure Database:
   Ensure that MySQL is running and create a database named finalsprint_db.
   Update the database configuration in src/main/resources/application.properties, If you choose a     
   different name.
3. Run the Application: Once your database is created, run the Main file.
4. Testing the API: Open Postman and perform a GET request on http://localhost:8080/ to see the available   
   links.

   
