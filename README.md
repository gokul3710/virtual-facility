# NestJS Microservices Project

Welcome to the NestJS microservices project! This repository contains a collection of code and resources related to building microservices-based applications using NestJS.

## Table of Contents

1. [Introduction](#introduction)
2. [Key Features](#key-features)

## Introduction

This project is a showcase of building microservices architecture with NestJS, focusing on various aspects such as SOA architecture, hybrid apps, health checks, validation pipes, common libraries, message queue systems (NATS and RabbitMQ), communication paradigms (request-response and event-driven), custom transporters, standalone apps, orchestration vs choreography, consistency patterns (outbox vs inbox), and distributed tracing.

It's worth noting that this project draws inspiration and incorporates learnings from the official NestJS course on microservices.

## Key Features

- **Service-Oriented Architecture (SOA)**: Implementing microservices architecture to build scalable and modular applications.
- **Hybrid Apps**: Combining monolithic and microservices architectures for flexibility and efficiency.
- **Health Check**: Implementing health checks for monitoring the status of microservices.
- **Common Libraries**: Sharing common libraries and utilities across microservices for code reusability.
- **Message Queue Systems**:
  - **NATS**: Implementing 1-N and 1-1 message publishing using NATS for efficient communication.
  - **RabbitMQ**: Ensuring message acknowledgment manually with channel.ack and channel.nack in case of failures.
- **Communication Paradigms**:
  - **Request-Response**: Implementing synchronous communication between microservices.
  - **Event-Driven**: Implementing asynchronous communication using events and message queues.
- **Standalone Apps**: Developing standalone microservices that can operate independently.
- **Orchestration vs Choreography**: Understanding different approaches for managing transactions in distributed systems.
- **Consistency Patterns**:
  - **Outbox Pattern**: Implementing outbox pattern for maintaining consistency in distributed systems.
  - **Inbox Pattern**: Understanding the inbox pattern and its implications on consistency.
- **Distributed Tracing**: Gaining insights into tracing and monitoring microservices interactions for debugging and optimization.
