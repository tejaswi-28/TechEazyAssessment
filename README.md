# TechEazyAssessment

# My AdminPanel

This project is an Angular frontend application designed to interact with a Spring Boot backend. It includes components for displaying and managing subjects and students.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- **Node.js** and **npm**: Make sure you have Node.js and npm installed. You can download them from [Node.js](https://nodejs.org/).
- **Angular CLI**: Install Angular CLI globally if you haven't already.

```sh
npm install -g @angular/cli

# Installation

1.Clone the repository:
  - git clone https://github.com/yourusername/my-angular-frontend.git

2.Navigate to the project directory:
  - cd admin-panel

3.Install dependencies:
  - npm install
  - Ensure you have node_modules file available in the project

#Running the Application

1.Start the Angular development server:
  - ng serve

2.Open your browser and navigate to:
  - http://localhost:4200

3.Go to login:
  - enter any of the below username :
                      * student.user
                      * admin.user
                      * invalid .user
4. Students
  - After login go to students in navbar
  - login using above username
  - Click on fetch students and refresh
  - the data will be shown after refresh


# **TechEazy-Backend**

# Spring Boot Backend

This project is a Spring Boot backend application that provides a REST API for managing students and subjects. It uses an H2 in-memory database for data storage.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- **Java Development Kit (JDK)**: Make sure you have JDK 19 or higher installed. You can download it from [Oracle](https://www.oracle.com/java/technologies/javase-jdk19-downloads.html) or [OpenJDK](https://jdk.java.net/19/).
- **Maven**: Ensure Maven is installed. You can download it from [Maven](https://maven.apache.org/).

## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. **Clone the repository**:

```sh
git clone https://github.com/yourusername/my-spring-boot-backend.git

1.Navigate to the project directory:
  -cd subject-students

2.Build the project
  - cd subject-students

# Run the application
1.Start the Spring Boot application:
  - mvn spring-boot:run

2.Access the H2 database console:
  - http://localhost:8080/h2-console
  -JDBC URL: jdbc:h2:mem:testdb
  -Username: sa
  -Password: password


-- Ensure that your SpringBoot project and angular project are in running state
-- refresh is compulsory after click on fetch data
-- JWT Tokens are not used in the following project
