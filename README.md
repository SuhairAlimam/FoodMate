<div align="center">

# 🍱 FoodMate

### Rescue surplus food. Save money. Fight waste.

FoodMate is a full-stack mobile application inspired by **Too Good To Go** — connecting customers with nearby restaurants and stores that have surplus food available at discounted prices, reducing food waste one bag at a time.

[![Flutter](https://img.shields.io/badge/Mobile-Flutter-02569B?style=flat&logo=flutter&logoColor=white)](https://github.com/SuhairAlimam/FoodMate_app)
[![Laravel](https://img.shields.io/badge/API-Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)](https://github.com/SuhairAlimam/FoodMate_API)
[![React](https://img.shields.io/badge/Dashboard-React-61DAFB?style=flat&logo=react&logoColor=black)](https://github.com/SuhairAlimam/FoodMate_React)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)]()
[![PHP](https://img.shields.io/badge/PHP%208.2-777BB4?style=flat&logo=php&logoColor=white)]()

</div>

---

## 📦 Project Repositories

This project is split into three repositories, each representing a separate layer of the system:

| Repository | Description | Tech Stack |
|---|---|---|
| [FoodMate_app](https://github.com/SuhairAlimam/FoodMate_app) | Mobile app for customers & store owners | Flutter, Dart |
| [FoodMate_API](https://github.com/SuhairAlimam/FoodMate_API) | RESTful backend API | Laravel 12, PHP 8.2, Sanctum |
| [FoodMate_React](https://github.com/SuhairAlimam/FoodMate_React) | Admin dashboard | React, TypeScript, Tailwind CSS |

---

## 🌍 The Problem

Every day, tons of perfectly good food is thrown away by restaurants, bakeries, and grocery stores simply because it didn't sell. At the same time, many people are looking for affordable meal options. FoodMate bridges that gap.

---

## ✨ Features

### 👤 For Customers
- Register and log in securely
- Browse nearby stores and restaurants with available surplus food
- View and purchase discounted food bags at reduced prices

### 🏪 For Store Owners
- Submit a store registration request
- Log in and manage surplus food listings
- Reach customers who want to rescue food

### 🛠️ For Admins
- Review and approve/reject store registration requests
- Monitor and manage all store listings via the React dashboard
- Full control over the platform through a dedicated admin panel

---

## 🏗️ System Architecture

```
┌─────────────────────┐     ┌──────────────────────┐
│   Flutter App       │     │   React Admin Panel  │
│  (Customers &       │────▶│   (Admin Dashboard)  │
│   Store Owners)     │     └──────────────────────┘
└────────┬────────────┘              │
         │                          │
         ▼                          ▼
┌──────────────────────────────────────────────────┐
│              Laravel RESTful API                 │
│         (Authentication via Sanctum)             │
│  ┌────────────┬──────────────┬─────────────────┐ │
│  │  Customer  │    Store     │     Admin       │ │
│  │   Routes   │   Routes     │    Routes       │ │
│  └────────────┴──────────────┴─────────────────┘ │
└──────────────────────────────────────────────────┘
```

---

## 🔐 Authentication & Roles

The API uses **Laravel Sanctum** for token-based authentication with three distinct roles:

- **Customer** — browse and purchase food bags
- **Store** — manage surplus food listings
- **Admin** — platform management and store approvals

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Mobile App | Flutter (Dart) |
| Backend API | Laravel 12, PHP 8.2 |
| Authentication | Laravel Sanctum |
| Admin Dashboard | React 18, TypeScript, Tailwind CSS, Vite |
| Architecture | RESTful API, MVC |

---

## 👨‍💻 Author

**Suher Ahmed Hassen**
- GitHub: [@SuhairAlimam](https://github.com/SuhairAlimam)

---

<div align="center">
  <i>Graduation Project — Built with ❤️ to reduce food waste</i>
</div>
