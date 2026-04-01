# JPA – Introduction and Implementation

🔗 **Related Course:**
[https://stahe.github.io/en-jpa-juin-2007/](https://stahe.github.io/en-jpa-juin-2007/)

---

## Overview

This document provides an introduction to the fundamental concepts of **data persistence using the JPA (Java Persistence API)**.

After studying and experimenting with the provided examples, the reader will have the necessary foundation to use JPA independently.

JPA was introduced with **Java 5 (JDK 1.5)** and is part of a multi-tier software architecture.

---

## Multi-tier Architecture

This document is based on a classic three-tier architecture:

* **[ui]** — User interface (Swing, console, web)
* **[business]** — Business logic
* **[DAO]** — Access to persistent data
* **[JDBC]** — Low-level database access

The goal of JPA is to standardize and simplify the **DAO** layer.

---

## ORM and Standardization

Before JPA, solutions such as **Hibernate** or **Toplink** offered ORM (Object Relational Mapping) mechanisms.

JPA introduces a **standard specification**:

* The DAO layer communicates with a **JPA interface**
* The implementation can be Hibernate, Toplink, etc.
* The business logic remains independent of the ORM provider

---

## Topics Covered

This document covers the following topics:

### 1️⃣ Relational/Object Mapping

Configuration via Java 5 annotations to manage:

* **One-to-one** relationships
* **One-to-many** relationships
* **Many-to-many** relationships

---

### 2️⃣ Java SE Environment

* Test console applications
* Direct manipulation of the JPA API
* Introduction to key methods (CRUD)

---

### 3️⃣ Advanced multi-tier architecture

Integration of:

* **Spring**
* **JBoss EJB3**

Use of:

* Connection pools
* Transaction managers
* Dependency injection
* Annotated POJOs

---

### 4️⃣ Web Application Example

The document concludes with a three-tier web application integrating:

* Web
* Business Logic
* DAO
* JPA
* ORM Implementation
* Spring Framework

---

## Learning Objectives

This material aims to:

* Understand the role of JPA in an enterprise architecture
* Master relational/object mapping
* Use JPA in SE and EE environments
* Compare Spring and EJB3 for managing technical services

---

## Target Audience

Java developers who wish to:

* Understand the basics of persistence with JPA
* Properly structure a multi-tier architecture
* Prepare to advance their skills toward Java EE

---

## Author

**Serge Tahé** – June 2007

---
