# Todo App
## Description
Todo App is a simple web application built using Spring Boot framework. It allows users to manage their tasks by adding, updating, and deleting todos. The application uses a PostgreSQL database to store todo items.

## Installation
### Spring Boot Installation
To run the Todo App, you need to have Spring Boot installed on your system. Follow the steps below to install Spring Boot:

### Visit the Spring Boot official website.
Download the latest version of Spring Boot.
Follow the installation instructions provided for your operating system.
Running the Application
Clone the repository to your local machine:

bash
Copy code
git clone <repository-url>
Navigate to the project directory:

bash
Copy code
cd todo-app
Build the project using Maven:

Copy code
mvn clean install
Run the application:

bash
Copy code
java -jar target/todo-app.jar
Once the application is running, you can access it at http://localhost:8080.

## Database Access
The PostgreSQL database used by the Todo App can be accessed via the H2 console. Follow the steps below to access the H2 console:

Visit http://localhost:8080/h2-console in your web browser.

## Enter the following details:

JDBC URL: jdbc:h2:mem:testdb
User Name: admin
Password: password
Click on the "Connect" button to access the database.

## Running the Application
Run the application:

Copy code
java -jar target/todo-app.jar
Once the application is running, you can access it at http://localhost:8080.

![image](https://github.com/Ammaar19/SpringBoot-TodoApp/assets/117352598/7a7c41c0-d645-4d09-962e-197fc40f3f6c)


## Project Structure
src/main/java: Contains the Java source code, including Spring Boot application files.
src/main/resources: Contains application properties, static files, and templates.
src/main/resources/static: Contains static resources such as HTML, CSS, JavaScript files.
src/main/resources/templates: Contains Thymeleaf templates for server-side rendering.

![image](https://github.com/Ammaar19/SpringBoot-TodoApp/assets/117352598/53ad5fe9-8859-4b30-a57c-b1251611e35c)


### How to Use
Open your web browser and navigate to http://localhost:8080.
Use the user interface to interact with the Todo App.
Perform operations like adding, updating, and deleting todos as needed.

![image](https://github.com/Ammaar19/SpringBoot-TodoApp/assets/117352598/a51f871a-55b2-4940-88f0-b45f10d7c261)

![image](https://github.com/Ammaar19/SpringBoot-TodoApp/assets/117352598/fdd2028c-3d63-4270-b741-70085fc9357b)

![image](https://github.com/Ammaar19/SpringBoot-TodoApp/assets/117352598/e8e651c8-d0da-444b-b13b-9caee55f245e)

![image](https://github.com/Ammaar19/SpringBoot-TodoApp/assets/117352598/cf8dc491-50ee-4d16-85fc-8c0819097570)





## Technologies Used
Spring Boot: Backend framework for building web applications in Java.
HTML: Markup language for creating the structure of web pages.
CSS: Styling language used to enhance the appearance of HTML elements.
## Contributor
Ammaar Sohail

# Video of the App


https://github.com/Ammaar19/SpringBoot-TodoApp/assets/117352598/3300f65a-c259-42cc-bbe8-ec43e362ffad


