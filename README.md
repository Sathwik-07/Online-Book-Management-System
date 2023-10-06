# OnlineBook-Management-System


Welcome to my Online Book Management System! This web application allows users to easily manage a collection of books by performing various operations like adding, updating, deleting, and displaying book details.

# Features

![Screenshot (167)](https://github.com/Sathwik-07/Online-Book-Management-System/assets/130444732/fe924b3b-0b3b-4ab1-bb54-28e55b5ce074)


### Adding New Book Details: 
Users can input information about a new book, including book name, book price and Author name.
![Screenshot (169)](https://github.com/Sathwik-07/Online-Book-Management-System/assets/130444732/ea72d706-e869-4e78-9190-b77b86ff60b7)

![Screenshot (168)](https://github.com/Sathwik-07/Online-Book-Management-System/assets/130444732/9159ce7a-d96a-4f4f-9d8c-56b454df13dd)

After adding the book details we can see the Book details inside the data base 

![Screenshot (162)](https://github.com/Sathwik-07/Online-Book-Management-System/assets/130444732/e71a8632-01d6-4651-8f95-cb8a8ee15381)




### Updating the Book Details: 
Modify existing book information such as book name, book price and Author name.


### Deleting  Book Details: 
Remove a book entry from the collection.

### Displaying the  Book Details: 
View a list of all the books in the collection with their respective details with the help of book id.

# Technologies Used

This Online Book Management System is built using a one-tier architecture, where all components are located on a single machine. Here's an elaborate explanation of the technologies used and the architecture:

## 1. Java Servlets:

In this project Java Servlets play a critical role in processing user requests, capturing HTML form data, and interacting with the database. They are responsible for handling various operations such as adding new book details, updating existing information, deleting book entries, and displaying book details.
In this application, servlets process user requests, interact with the database, and generate dynamic web content.


## 2. MySQL:

MySQL is employed as the relational database management system. It stores all the book details, including titles, authors, genres, and other relevant information. The application interacts with the MySQL database to perform CRUD operations on the book collection.

## 3. HTML/CSS/Bootstrap:

HTML, CSS, and Bootstrap are used to create the user interface and style the web pages. HTML is used for structuring the content, CSS for styling, and Bootstrap for responsive design and layout. This trio helps in presenting an intuitive and visually appealing interface to the users.

## 4. Database Connectivity:
Java Database Connectivity (JDBC) is utilized to establish a connection between the Java application and the MySQL database. JDBC is a standard Java API for database-independent connectivity. Type 1 driver is used for this purpose, which relies on the JDBC-ODBC bridge to connect to the database.

# Additional Details:

## a. One-Tier Architecture:
The one-tier architecture, also known as the single-tier architecture, involves deploying all the application components (presentation, application logic, and data management) on a single machine. In this case, the Java Servlets, handling both presentation and application logic, are directly connected to the MySQL database.

## b. Integrated Development Environment (IDE):
Eclipse IDE is used for development. It provides a comprehensive development environment for Java applications, aiding in coding, testing, and debugging.

## c. MySQL Connector/J (External JAR):

MySQL Connector/J is an external JAR (Java Archive) file that serves as the official JDBC (Java Database Connectivity) driver for MySQL. This connector allows Java applications, like our Online book management system, to connect and interact with the MySQL database.

## d. Web Server:

Apache Tomcat Server version 9.0 is used to host and deploy this Project. Tomcat is responsible for serving the web application and managing the servlets, JSP pages, and other resources.

Overall, these technologies, along with the one-tier architecture, Eclipse IDE, MySQL Connector/J, and Apache Tomcat Server version 9.0, form the backbone of this project  enabling its functionality and user interface.


# Usage

After successfully deploying the project, you can access this Online book management through a web browser. Simply navigate to the application's URL. Once there, you can perform the following actions:

### Add a Book: 
Provide book details to add a new entry.

### Update Book Details: 
Modify existing book information as needed.

### Delete a Book: 
Remove a book from the collection.

### Display Book Details: 
View the complete list of books and their details.
