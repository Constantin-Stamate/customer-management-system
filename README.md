# Customer Management App

This Java application is a **Customer Management System** built using **Spring Boot**, offering RESTful endpoints to manage customers, products, and orders. All operations are exposed via a clean API interface and are testable using **Swagger UI**.

## Project Context

This project was developed as part of the **Object-Oriented Programming** course at the **Technical University of Moldova (UTM)**.  
It served as a practical exercise to explore **Spring Boot** and RESTful web services, focusing on implementing core backend features using **JDBC** for database interaction, without using Spring Data JPA.

## Features Implemented

- CRUD operations via REST endpoints for:
    - Customers
    - Products
    - Orders
- REST API built with Spring Web
- Integration with **Swagger UI** for easy testing
- Data access implemented using **JDBC**
- Clear separation between controllers, services, and repositories
- Basic error handling and validation

## How to Run the Project

1. **Install Java**

   Download and install Java 11 or later: [https://www.oracle.com/java/technologies/javase-downloads.html](https://www.oracle.com/java/technologies/javase-downloads.html)


2. **Install Maven**

   If your project **does not include** a Maven Wrapper (`mvnw`, `mvnw.cmd`), you need to install Maven manually.

   Download and install Apache Maven: [https://maven.apache.org/](https://maven.apache.org/)

   > ⚠️ Skip this step if your project contains a `mvnw` file — in that case, you can use the wrapper directly without installing Maven globally.
   
3. **Clone the repository**

```bash
  git clone https://github.com/Constantin-Stamate/Customer_Management_App.git
```

4. **Navigate to the project folder**

```bash
  cd Customer_Management_App
```

5. **Run the application with Maven (Linux/macOS)**

```bash
  ./mvnw spring-boot:run
```

6. **Run the application with Maven (Windows)**

```bash
  mvnw.cmd spring-boot:run
```

7. **Access Swagger UI**

   Open your browser and navigate to: [http://localhost:8080/swagger-ui/index.html](http://localhost:8080/swagger-ui/index.html)

   You can test all available endpoints for:
   - `/customers`
   - `/products`
   - `/orders`

## Useful Links

- [Spring Boot Reference Guide](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
- [Swagger UI Docs](https://swagger.io/tools/swagger-ui/)
- [JDBC Basics](https://docs.oracle.com/javase/tutorial/jdbc/)

## Author

This project was developed by **Constantin Stamate** as part of the **Object-Oriented Programming** course at the **Technical University of Moldova (UTM)**, exploring **Spring Boot** and **JDBC** backend development.

- GitHub: [Constantin-Stamate](https://github.com/Constantin-Stamate)
- Email: [constantinstamate.r@gmail.com](mailto:constantinstamate.r@gmail.com)