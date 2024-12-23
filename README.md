# CreditCardEligibility

**CreditCardEligibility** is a legacy Spring Framework application designed to determine whether a user is eligible for a credit card based on predefined eligibility criteria. This application uses traditional XML-based Spring configuration and JSP for the frontend.

---

## Features

- **Credit Card Eligibility Check**: Evaluates user inputs against eligibility criteria.
- **Dynamic User Interface**: Built using JSP for seamless user interaction.
- **Legacy Spring Framework**: Utilizes XML-based configuration for dependency injection and bean management.

---

## Prerequisites

To set up and run the application, ensure that the following software is installed on your system:

1. **Java**: JDK 8 or higher.
2. **Apache Tomcat**: Version 8 or above.
3. **Maven**: For dependency management and project building.

---

## Getting Started

### Steps to Set Up the Application on Your System

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ChethanKacham/CreditCardEligibility.git
   
2. **Navigate to the Project Directory**
   ```bash
   cd CreditCardEligibility

3. **Build the Project**
   ```bash
   mvn clean package

4. **Deploy to Apache Tomcat**
   - Copy the generated WAR file (located in the target directory) to the webapps folder of your Tomcat server.
   - Example: 
     ```bash
	 Copy the generated WAR file (located in the target directory) to the webapps folder of your Tomcat server.

5. **Start the Tomcat server**  Navigate to your Tomcat installation directory and start the server:
   ```bash
   .\bin\startup.bat

6. **Access the Application** Open your browser and navigate to: http://localhost:8080/CreditCardEligibility

## Application Workflow

1. Enter your PAN number into the form.

2. Submit the form to check your eligibility for a credit card.

3. View the result indicating whether you meet the eligibility criteria.

## 🛠️ Technologies Used

   - **Backend**: Legacy Spring Framework (XML-based configuration)
   - **Frontend**: JSP(Java server pages)
   - **Database**: H2(Default in-memory database using Hibernate)
   - **Server**: Apache Tomcat server
   - **Build Tool**: Maven