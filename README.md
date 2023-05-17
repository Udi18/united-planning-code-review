# Coding Exercise for Full Stack Senior Dev Position

## Overview

This document provides a set of three potential coding exercises for evaluating the proficiency of candidates for a senior full-stack developer position. The exercises cover essential aspects of our tech stack, which includes C# .NET for the backend, TypeScript with Next.js for the front-end, and SQL for database operations. 

Our expectation is not necessarily for candidates to complete all steps within each exercise, but to demonstrate their understanding of the languages and coding concepts, data management and security, as well as testing principles.

## Exercise 1: Secure API Development

### Overview:

Develop a secure RESTful API using C# .NET which performs CRUD operations on a database. This API will manage a collection of `Book` entities with the following fields: `Id`, `Title`, `Author`, `ISBN`, and `PublishYear`.

### Tasks:

1. Design and create the SQL schema for the `Book` entity.
2. Implement CRUD operations.
3. Implement input validation and exception handling.
4. Ensure secure access to the endpoints via an authentication and authorization mechanism.
5. Write unit tests for your API endpoints.

## Exercise 2: Data-Driven Web Application

### Overview:

Build a Next.js application that interacts with the previously created API. The app should provide an interface for users to view, create, update, and delete books.

### Tasks:

1. Design a responsive UI using a modern framework or your own styles.
2. Implement pages for listing, creating, updating, and deleting books.
3. Add client-side input validation.
4. Handle API errors gracefully and inform the user.
5. Implement secure authentication to access the API.
6. Write unit and integration tests for your components and pages.

## Exercise 3: Complex SQL Queries

### Overview:

Assume we have two tables in a relational database: `Orders` and `OrderItems`. The `Orders` table has fields `Id`, `CustomerId`, and `OrderDate`. The `OrderItems` table has fields `Id`, `OrderId`, `ProductId`, `Quantity`, and `Price`.

### Tasks:

1. Write a SQL query to retrieve all orders for a specific customer.
2. Write a SQL query to calculate the total cost of an order.
3. Write a SQL query to find the top 5 selling products.
4. Write a SQL query to find all customers who haven't placed an order within the last year.
5. Explain how indexes could improve the performance of your queries, and where you would add them.

## Submission Instructions

1. Fork the pre-scaffolded GitHub repository for this exercise.
2. Complete the tasks for each exercise as outlined above.
3. Document your process, design choices, any assumptions you made, and areas where you would add further improvements if given more time.
4. Create a pull request against the original repository with your completed tasks and documentation.
5. We'll review your submission and discuss it with you during the follow-up interview.

We value quality over quantity. If you're unable to complete all tasks within the day, prioritize completing a smaller number of tasks well and documenting your approach and next steps for the remaining tasks. Good luck!