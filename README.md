# 🚗 Garage Management System

Modern Garage Management System built with **WPF .NET 8**, **Laravel 13 API**, and **MySQL Database**.

A complete business management solution designed for garages, POS systems, coffee shops, and multi-branch businesses.

---

## ✨ Features

### 🔐 Authentication

* User Login
* API Authentication
* Laravel Sanctum Token
* Change Password
* User Profile

### 🏢 Branch Management

* Main Branch
* Sub Branch
* Multi-Branch Support
* Branch Configuration

### 👥 User Management

* User Roles
* User Permissions
* Activity Logs
* Access Control

### 📊 Dashboard

* Sales Overview
* Customer Statistics
* Product Statistics
* Branch Statistics
* Recent Activities

### 🎨 Modern UI

* Material Design
* Responsive Layout
* Modern Dashboard
* Dark/Light Theme Ready
* Professional Icons

### 🔄 Auto Update

* GitHub Release Check
* Version Control
* Update Notification
* Download Latest Version

---

## 🛠 Technology Stack

### Frontend

* WPF .NET 8
* C#
* XAML
* Material Design In XAML Toolkit

### Backend

* Laravel 13
* PHP 8.4+
* REST API
* Laravel Sanctum

### Database

* MySQL
* Stored Procedures
* Views

### Tools

* Visual Studio 2026 Enterprise
* Visual Studio Code
* GitHub
* Postman

---

## 🏗 System Architecture

```text
WPF Desktop Application
           │
           ▼
      REST API
           │
           ▼
      Laravel 13
           │
           ▼
         MySQL
```

---

## 📂 Project Structure

```text
GarageManagementSystem
│
├── Assets
│   ├── Icons
│   └── Images
│
├── Alerts
├── Class
├── Models
├── Services
├── Dashboard
├── Users
├── Reports
│
├── MainWindow.xaml
├── FrmUserLogin.xaml
├── App.xaml
│
└── README.md
```

---

## 🔑 API Authentication

### Login Request

```http
POST /api/v1/login
```

### Request Body

```json
{
  "username": "admin",
  "password": "123456"
}
```

### Response

```json
{
  "success": true,
  "message": "Login Successfully",
  "token": "xxxxxxxxxxxxxxxx",
  "user": {
    "userid": "001",
    "name": "Administrator"
  }
}
```

---

## 📡 API Modules

| Module             | Endpoint                              |
| ------------------ | ------------------------------------- |
| Login              | POST /api/v1/login                    |
| Profile            | GET /api/v1/profile                   |
| Products           | GET /api/v1/products                  |
| Store Registration | POST /api/v1/store/register           |
| System Information | GET /api/v1/setting/combo/system_info |

---

## 💻 Installation

### Clone Repository

```bash
git clone https://github.com/reanprogramming/garage-system.git
```

### Open Project

```bash
Visual Studio 2026 Enterprise
```

### Restore Packages

```bash
dotnet restore
```

### Build Project

```bash
dotnet build
```

### Run Project

```bash
dotnet run
```

---

## 📸 Screenshots

### Login Screen

* Modern Material Design UI
* API Authentication
* User Validation

### Dashboard

* Statistics Cards
* Quick Actions
* Business Overview

---

## 🚀 Roadmap

### Completed

* User Login
* Laravel API Integration
* Material Design UI
* Branch Management
* User Management
* Dashboard

### Upcoming

* Sales Module
* Inventory Module
* Purchase Module
* Reporting Module
* Telegram Notifications
* Flutter Mobile Application
* Online Synchronization

---

## 📱 Future Mobile Application

Flutter Mobile App:

* Android Support
* iOS Support
* Material 3 Design
* API Integration
* Dashboard
* Products
* Sales Reports

---

## 👨‍💻 Developer

**JOIN CODER**

GitHub:
https://github.com/reanprogramming

Telegram:
https://t.me/reansourcecode

YouTube:
https://youtube.com/@joincoder

---

## 📄 License

This project is licensed under the MIT License.

Copyright © 2026 JOIN CODER.
