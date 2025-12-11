# Workforce Management Platform — Timecard &amp; People Services

Summary

Contributed to a cloud-based Workforce Management product across Timecard and People domains. Designed scalable microservices, REST APIs, payroll batch processes, and React-based UI workflows. The system supported multi-tenant architecture, secure routing, and high availability across distributed components.

Architecture & Responsibilities
  Backend & Microservices (Node.js, Java, Cloud)
  
    1. Designed and implemented REST APIs for Timecard management and People data services.
    2. Built cloud-native microservices with a tenant management system ensuring strict data isolation.
    3. Used API Gateway for routing, authentication/authorization, and traffic control.
    4. Integrated Redis cache to reduce response times and improve throughput for read-heavy operations.
    5. Implemented RabbitMQ for asynchronous, event-driven communication across services.
    6. Created payroll batch jobs to automate calculation and processing cycles.
    7. Leveraged Google Load Balancer to distribute incoming traffic for high availability.
    8. Managed persistence using PostgreSQL, including tenant-aware schema handling.
    9. Utilized Splunk and Dynatrace for real-time monitoring, log analysis, performance tuning, and debugging across services.

  Frontend (React)

    1. Built React components and workflows for timecard entry, approvals, and employee data management.
    2. Implemented responsive UI flows allowing employees and managers to track hours, update records, and trigger payroll actions.

Key Features

  1. Multi-tenant workforce management with cloud-native scaling
  2. Timecard capture, approval workflow, and audit trails
  3. People data & employee profile services
  4. Automated payroll batch processing
  5. Event-driven microservice communication via RabbitMQ
  6. High-throughput, low-latency endpoints using Redis
  7. Secure, centralized routing and auth via API Gateway
  8. End-to-end monitoring and debugging with Splunk & Dynatrace

Tech Stack

  Java, Node.js, React, Redis, RabbitMQ, PostgreSQL, API Gateway, Google Load Balancer, Splunk, Dynatrace, Microservices, Cloud Architecture


a diagram section for GitHub

or convert this into a clean architectural diagram using Mermaid

Just tell me what you need.
