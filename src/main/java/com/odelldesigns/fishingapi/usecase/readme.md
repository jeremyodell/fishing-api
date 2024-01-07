# Usecase Package

## Overview
The `usecase` package encapsulates the business logic of the application. It defines the application's core functionalities, following the Clean Code principles and the Single Responsibility Principle (SRP).

## Responsibilities
- Defining classes and methods that represent the business actions and rules.
- Interacting with the `gateway` package to retrieve and persist data.
- Encapsulating business logic away from the web layer and data access layer.

## Best Practices
- Follow the SRP by ensuring each use case class has one responsibility.
- Write unit tests for business logic to ensure reliability and maintainability.
- Keep use case classes independent of frameworks and libraries.
