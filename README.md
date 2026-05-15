<div align="center">
  <img src="frontend-web/public/logo-mark.svg" alt="Inventory Sales Hub Logo" width="120" />

  <h1>Inventory & Sales Hub</h1>

  <p>
    <strong>A comprehensive, full-stack enterprise platform for inventory, sales, and point-of-sale (POS) management.</strong>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot" alt="Spring Boot" />
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
    <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  </p>
</div>

<br />

## 📖 About The Project

**Inventory & Sales Hub** is a robust, scalable system designed to streamline business operations. Built with a microservices-inspired approach within a monorepo structure, it provides a seamless experience across web and mobile platforms. 

Whether it's processing transactions through the POS, auditing stock movements, or analyzing sales metrics, this platform delivers enterprise-grade tools tailored for modern businesses.

### ✨ Key Features

- **🛒 Point of Sale (POS):** Efficient checkout system with session management and cart functionalities.
- **📦 Inventory Management:** Real-time stock tracking, automated low-stock alerts, and warehouse transfers.
- **📊 Analytics Dashboard:** Comprehensive insights into revenue, top products, and employee performance.
- **👥 Role-Based Access Control (RBAC):** Secure access management for Admins, Managers, and Staff.
- **📱 Cross-Platform:** Native mobile application for on-the-go management alongside a powerful web portal.
- **🛡️ Audit & Security:** Detailed audit logs for all entity modifications and secure JWT-based authentication.

---

## 📸 Screenshots

> **Note:** Add your actual project screenshots here. Good visuals are key to a professional presentation!

<div align="center">
  <img src="https://via.placeholder.com/800x400?text=Web+Dashboard+Screenshot" alt="Dashboard Preview" width="100%" />
  <br />
  <em>Web Analytics Dashboard</em>
</div>

<br />

<div align="center">
  <img src="https://via.placeholder.com/250x500?text=Mobile+App" alt="Mobile Preview" width="30%" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://via.placeholder.com/250x500?text=Mobile+POS" alt="Mobile POS" width="30%" />
</div>

---

## 🏗️ Architecture & Tech Stack

This project is structured as a monorepo containing three main modules:

### 1. Backend Service (`/backend-service`)
- **Framework:** Java 17, Spring Boot 3
- **Database:** PostgreSQL
- **Security:** Spring Security, JWT Tokens
- **Build Tool:** Gradle

### 2. Frontend Web (`/frontend-web`)
- **Core:** React 18, Vite
- **Language:** TypeScript
- **Styling:** SCSS Modules
- **Testing:** Playwright (E2E), Vitest

### 3. Frontend Mobile (`/frontend-mobile`)
- **Core:** React Native
- **Language:** TypeScript
- **Build/Run:** Metro, Android/iOS native builds

---

## 🚀 Getting Started

Follow these steps to set up the project locally for development and testing.

### Prerequisites
- [Node.js](https://nodejs.org/) (v18+)
- [Java JDK 17](https://adoptium.net/)
- [Docker](https://www.docker.com/) & Docker Compose
- [PostgreSQL](https://www.postgresql.org/)

### Installation

**1. Clone the repository:**
```bash
git clone [https://github.com/yourusername/inventory-sales-hub.git](https://github.com/yourusername/inventory-sales-hub.git)
cd inventory-sales-hub
