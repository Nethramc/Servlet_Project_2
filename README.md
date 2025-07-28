# Servlet_Project_2

A Java web application using Servlets and HTML. This project demonstrates dynamic web functionality using Java Servlets, with a front-end built in HTML.

## Features

- Java Servlets for backend logic
- HTML for front-end interface
- Example of simple Servlet-based web application

## Technologies Used

- **Java**: Main programming language for backend logic.
- **Java Servlet API**: For handling HTTP requests and responses, and building web components.
- **HTML**: For creating the user interface and web pages.
- **Maven**: Project management and build tool for dependency management and building the application.
- **Eclipse IDE**: Integrated Development Environment for code editing, building, and deploying.
- **Apache Tomcat** (configured in Eclipse): Servlet container to run and test the application.

## How It Works

1. **User Request**: When a user accesses the application via a web browser, an HTTP request is sent to the server.
2. **Servlet Processing**: The Java Servlet receives the request, processes any business logic, interacts with data if needed, and prepares a response.
3. **Response Generation**: The Servlet forwards the response—often an HTML page—back to the user's browser.
4. **Front-End Display**: HTML files in the project define how information is displayed to the user.
5. **Container Deployment**: The application runs on Apache Tomcat, which manages the lifecycle of Servlets and handles routing between requests and responses.

## Project Setup (Maven & Eclipse)

### Prerequisites

- **Java JDK 8+**
- **Eclipse IDE for Enterprise Java Developers**
- **Apache Tomcat (configured in Eclipse)**
- **Maven (built-in with Eclipse or standalone)**

### Steps to Run

#### 1. Clone the Repository

```bash
git clone https://github.com/Nethramc/Servlet_Project_2.git
```

#### 2. Import Project into Eclipse

1. Open Eclipse.
2. Go to `File` > `Import...` > `Maven` > `Existing Maven Projects`.
3. Select the cloned folder. Click `Finish`.

#### 3. Configure Tomcat

1. In Eclipse, go to `Window` > `Preferences` > `Server` > `Runtime Environments`.
2. Add and configure your Apache Tomcat server.

#### 4. Run the Application

1. Right-click the project > `Run As` > `Run on Server`.
2. Select your configured Tomcat server.
3. Access the app at:  
   `http://localhost:8080/Servlet_Project_2`

## Project Structure

```
Servlet_Project_2/
├── pom.xml
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── example/
│       │           └── servlet/
│       │               └── [YourServlets.java]
│       └── webapp/
│           ├── WEB-INF/
│           │   └── web.xml
│           └── [HTML files]
└── README.md
```

- **pom.xml**: Maven build configuration
- **src/main/java**: Java source code (Servlets)
- **src/main/webapp**: Web resources (HTML, JSP, etc.)
- **WEB-INF/web.xml**: Servlet configuration

---

**Author:** [Nethramc](https://github.com/Nethramc)
