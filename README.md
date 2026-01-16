# FredsBoats
Fred's Boats Reservation System

Here is a professional and descriptive text you can copy directly into your project's `README.md` file. It summarizes the business purpose, the technical stack, and the educational context of the application.

---

# 🚤 Fred's Boats Management System

**Fred's Boats** is a robust ASP.NET Core MVC web application designed to digitize and streamline the daily operations of a boat rental business.

This project serves as a comprehensive lab exercise for building data-driven web applications using modern .NET technologies. It demonstrates the full development lifecycle—from modeling complex database relationships (ER diagrams) to implementing CRUD (Create, Read, Update, Delete) functionality in a cloud-based environment.

## 🎯 Project Overview

The application manages the core entities required for a rental fleet:

* **Fleet Management:** Tracking individual boats, including their hourly/daily rates, specific colours, and categories (e.g., Sailing vs. Motor).
* **Customer Administration:** A secure registry of customer details, contact information, and boating license verification.
* **Reservations:** (Future implementation) A booking system linking customers to specific boats for defined time periods.

## 🛠️ Technology Stack

* **Framework:** .NET 9.0 (ASP.NET Core MVC)
* **Language:** C#
* **ORM:** Entity Framework Core
* **Database:** SQLite (Optimized for GitHub Codespaces/Dev environments)
* **Development Environment:** GitHub Codespaces (Linux-based container)

## 📂 Data Model

The system is built upon a relational database structure featuring:

* **Boats:** The central entity containing pricing and foreign keys to Categories and Colours.
* **Customers:** Stores personal data and license status.
* **Categories & Colours:** Lookup tables for standardized data entry.
* **Reservations:** Join tables connecting Customers to the Boats they rent.

## 🚀 Getting Started

This project is configured for instant deployment via **GitHub Codespaces**.

1. Fork the repository.
2. Launch a new Codespace.
3. Run the application using `dotnet run`.

---

### How to Fork the Repository

1. Click the Fork button (top right corner).
2. Click Create fork.
3. Launch Codespaces.
4. Click the green <> Code button.
5. Select the Codespaces tab.
6. Click Create codespace on main.
