# First-Java-CRUD

Simple CRUD application built with Spring Boot, Spring Data JPA, H2 and Vaadin.
Based on the guide [Creating CRUD UI with Vaadin](https://spring.io/guides/gs/crud-with-vaadin/).

## Features

- list customers in a table
- filter customers by last name
- add a new customer
- edit an existing customer
- delete a customer

## Requirements

- Java 21

## Run

Windows:

```
mvnw.cmd spring-boot:run
```

Linux / macOS:

```
./mvnw spring-boot:run
```

Then open http://localhost:8080 in the browser.

## Project structure

- `Customer` - JPA entity
- `CustomerRepository` - Spring Data repository
- `MainView` - main page with the table, filter and "New customer" button
- `CustomerEditor` - form for creating, editing and deleting a customer
- `CrudwithvaadinApplication` - entry point, loads sample data on startup

## Documentation

Screenshots are in the [doc](doc) directory.
