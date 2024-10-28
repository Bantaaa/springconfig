## SPRING FRAMEWORK

This application is a basic User Management System 
built using Spring Core without Spring Boot, 
Spring MVC, and Spring Data JPA. It allows users to perform CRUD operations 
such as creating, viewing, updating, and deleting users through a web interface.

## Table of Contents
- [Project Structure](#project-structure)
- [Dependency Injection (DI)](#dependency-injection-di)
- [Inversion of Control (IoC)](#inversion-of-control-ioc)
- [Spring Beans](#spring-beans)
- [Bean Scopes](#bean-scopes)
- [ApplicationContext](#applicationcontext)
- [Component Scanning and Stereotype Annotations](#component-scanning-and-stereotype-annotations)
- [Spring Data JPA](#spring-data-jpa)
- [Spring MVC](#spring-mvc)
- [Installation and Setup](#installation-and-setup)

### Project Structure

Dependency Injection (DI)
A design pattern where objects don't create their dependencies themselves, but receive them from outside (usually through constructor injection or setter injection), making code more maintainable and testable by reducing tight coupling between components.
Inversion of Control (IoC)
A programming principle where the control of program flow is transferred from your code to a framework (like Spring), which manages object creation, lifecycle, and wiring of dependencies, essentially "inverting" who's in control of object instantiation and management.
Spring Beans
Objects that are instantiated, assembled, and managed by the Spring IoC container, defined either through Java/XML configuration or component scanning annotations like @Component, @Service, or @Repository.
Bean Scopes
Defines how long a bean lives and how many instances of it exist in an application, with options like singleton (one instance shared across the application), prototype (new instance each time requested), request (per HTTP request), session (per user session), and application (per ServletContext).
ApplicationContext
The central interface within a Spring application that provides configuration for the entire application, including bean instantiation, dependency injection, and access to application components, essentially acting as the Spring IoC container.
Component Scanning and Stereotype Annotations
A Spring feature that automatically detects and registers beans based on annotations like @Component, @Service, @Repository, and @Controller, eliminating the need for manual bean registration in configuration files.
Spring Data JPA
A Spring module that simplifies database access by reducing boilerplate code through repository interfaces that automatically implement common database operations, supporting both JPA providers like Hibernate.
Spring MVC
A web framework built on the Model-View-Controller pattern that handles web requests through a central DispatcherServlet, which delegates to @Controllers for processing and returns views to be rendered in the browser.

### Installation and Setup
