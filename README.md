# Mina Electric - Software Requirements Specification (SRS)

This repository contains the **Software Requirements Specification (SRS)** document for the Mina Electric e-commerce project. The SRS defines the functional and non-functional requirements, system design models, and other critical details required to build the database-driven e-commerce platform.

---

## Overview

The e-commerce platform for Mina Electric is designed to digitalize a traditional wholesale business. The goal is to create an online platform that enables customers and retailers to browse products, place orders, and manage profiles efficiently. The SRS document provides a comprehensive guide for developers, project managers, and stakeholders to understand the system's requirements and design.

---

## SRS Content

The document includes the following sections:

1. **Introduction**
   - Purpose of the document
   - Project scope
   - Intended audience
   - Abbreviations and references

2. **Overall Description**
   - Product perspective
   - Product features
   - User classes and characteristics
   - Operating environment
   - Assumptions and dependencies
   - Risks and volatile areas

3. **Specific Requirements**
   - Functional requirements
   - Non-functional requirements
   - Database specifications

4. **System Models**
   - Use Case Diagram
   - Class Diagram
   - Activity Diagram
   - Sequence Diagram
   - Collaboration Diagram
   - Component Diagram
   - State Chart Diagram
   - Deployment Diagram

5. **Appendices**
   - Prototype designs for customer and admin views

---

## Key Highlights

### Functional Requirements
- **User Authentication**: Secure login and registration with role-based access.
- **Product Management**: CRUD operations for products and categories.
- **Order Management**: Cart, checkout, and order tracking functionality.
- **Search and Wishlist**: Efficient product search and wishlist feature.

### Non-Functional Requirements
- **Performance**: Page loads in under 2 seconds under normal conditions.
- **Scalability**: Supports up to 50,000 concurrent users.
- **Usability**: User-friendly interface for both customers and admin users.

### Database Design
- Normalized schema up to BCNF.
- Entities: Customers, Products, Categories, Orders, Reviews, and Admins.
- Features advanced SQL queries, transactions, and indexing for optimized performance.

### System Models
The SRS includes diagrams to illustrate the system architecture and workflows:
- Use Case Diagram: Shows user interactions.
- Class Diagram: Highlights relationships between system entities.
- Activity and Sequence Diagrams: Detail workflows like login, checkout, and admin actions.
- Deployment Diagram: Depicts system infrastructure.

---

## Prototype Previews

### Customer View
![Customer View](images/customer-view.png)

### Admin View
![Admin View](images/admin-view.png)

---

## How to Use This Repository

1. Clone the repository:
   ```bash
   git clone <repository-url>
