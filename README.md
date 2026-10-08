
This repository contains a Java web application built with Spring Boot, demonstrating server-side rendering using the Java Template Engine (JTE).

## Tech Stack
Language: Java
Framework:Spring Boot
Template Engine JTE (Java Template Engine)
Build Tool: Maven

 Repository Structure
The project follows a standard Spring Boot architecture integrated with JTE templates:
Controllers: `HomeController.java` handles routing.
Models: `Page.java` is used for view data.
Templates (`src/main/jte`):** Contains the views, including `home.jte`, `projects.jte`, `team.jte`, and a base layout in `layout/main.jte`.
 Running the Application Locally

1. Clone the repository:
   ```bash
   git clone [https://github.com/Vladimir-Iluk/](https://github.com/Vladimir-Iluk/)[YOUR_REPO_NAME].git
   cd [YOUR_REPO_NAME]
Run the application using the Maven Wrapper:

Linux/macOS:

Bash
./mvnw spring-boot:run
Windows:

DOS
mvnw.cmd spring-boot:run
Access the application in your browser at http://localhost:8080
