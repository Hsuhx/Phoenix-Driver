# Phoenix Driver Project MVP

## Introduction
Phoenix Driver is an innovative driver service platform primarily offering services such as driving after drinking, business driving, and long-distance driving. Leveraging the internet platform, users can easily access driving services. With the growth of private car ownership in China, the internet driving industry is developing rapidly. This project aims to fill this demand gap. Our competitive advantage is to provide safer driving services for customers.  Our future goal is to optimize services based on user feedback to improve user satisfaction.
 Our target for this semester is facial recognition: using AiFace for daily identity verification, ensuring the safety of both drivers and passengers through static and dynamic detection capabilities.

Driving after drinking: Ensuring users get home safely after drinking.
Business driving: Providing reliable driving services for business professionals.
Long-distance driving: Offering driving services for users needing long-distance travel.
Online booking: Users can book driving services through the WeChat Mini Program.
Real-time location tracking: Users can view the driver's location in real time.
Cost estimation: Providing trip cost estimation to help users understand the cost in advance.

## Core Features
### User Registration and Login: Users can register and log in using their phone numbers or WeChat accounts.
### Booking a Driver:
Driving after Drinking: Ensure users get home safely after consuming alcohol.
Business Driving: Provide reliable driving services for business professionals.
Long-Distance Driving: Offer driving services for long-distance travel needs.
### Online Booking: Users can book driving services through the WeChat Mini Program.
### Real-time Location Tracking: Users can view the driver's location in real time.
### Cost Estimation: Provide trip cost estimation to help users understand the cost in advance.
### Payment Integration: Seamless payment processing through WeChat Pay.
## User Interface (UI)
WeChat Mini Program: Users mainly operate through the WeChat Mini Program, including booking, viewing driver information, and paying fees.
Driver APP: Drivers receive orders, navigate, and manage personal information through a dedicated app.
Admin Dashboard: Administrators manage user and driver information, order management, financial statistics, etc., through the web management system.

## Technical Infrastructure
Spring Boot: Simplifies the initial setup and development process of applications.
Spring Cloud: Cloud-native application development tools based on Spring Boot.
MyBatis-Plus: Persistence layer framework.
Redis & Redisson: In-memory caching and data grid framework.
MongoDB: Distributed file storage database.
RabbitMQ: Message middleware to ensure final consistency of distributed transactions.
Seata: Distributed transaction management.
Drools: Rule engine.
GEO: Spatial partitioning and calculation based on GPS.
ThreadPoolExecutor + CompletableFuture: Asynchronous orchestration.
XXL-JOB: Distributed job scheduling center.
Knife4J/YAPI: API documentation tools.
MinIO: Private object storage cluster.
WeChat Pay: Payment and profit sharing.
MySQL: Relational database, using ShardingSphere-jdbc for read-write separation and database sharding.
Lombok: Used to generate getter/setter.
Docker: Containerization technology.
Git: Code management tool.
Frontend tech stack: Vue3, TypeScript, GraceUI, uniapp-axios adapter.

## Competitors
Didi Driver: High market share, strong brand awareness.
eDriver: Traditional driving service provider with stable services

## Target Audience
Business professionals: Need safe and fast driving services.
Family users: Inconvenient to drive after drinking, need safe delivery.
Long-distance travelers: Long-distance travelers needing driving services.
Elderly: Elderly people who find it inconvenient to drive for long periods.

## Future Development
Service optimization: Continuously optimize services based on user feedback to improve user satisfaction.

## Goal of the MVP
The goal of this semester is to build a designated driver system that realizes basic functions and strive to realize the basic facial recognition driver function to better ensure the safety of passengers.We also conducted some research on Australia’s data security and whether facial recognition and platform collection of user data are feasible in Australia. We also explored whether the project could be deployed in Australia.
