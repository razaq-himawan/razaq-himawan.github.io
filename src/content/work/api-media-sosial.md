---
title: Social Media API
publishDate: 2025-08-17 00:00:00
img: /assets/works/api-media-sosial.png
img_alt: Code snippet of the Social Media API project
description: |
  A backend API built with Go, Gin, and MySQL that supports user registration, login with JWT, creating posts, and adding comments. This project focuses on authentication, database relations, and building a clean API structure.
tags:
  - Go
  - Gin
  - MySQL
  - Backend
isFeatured: true
---

This project is a **simple social media REST API** built with Go. Users can register, log in securely with JWT authentication, create posts, and add comments. The goal was to strengthen backend skills in Go while practicing authentication, relational data modeling, and API design.

The app is structured using Gin for routing, GORM for database access, and MySQL as the data store. It follows a clean modular structure with `user`, `post`, and `comment` domains, making it easier to extend in the future.

### 🚀 Features

- 👤 User registration & login with JWT
- 📝 Create posts (with user association)
- 💬 Add comments to posts
- 🔒 Secure endpoints & input validation

### 🛠 Built With

- **Go (Golang)** – Backend language
- **Gin** – Web framework & routing
- **GORM** – ORM for MySQL
- **MySQL** – Database
- **JWT** – Authentication
- **Validator** – Request validation
- **godotenv** – Environment variable management

### 📚 What I Learned

- Structuring a Go project with clear modules (user, post, comment)
- Building secure authentication with JWT
- Designing relational models in GORM (User ↔ Post ↔ Comment)
- Validating input and handling errors gracefully
- Using environment variables for configuration

### 🔗 Links

[![GitHub Repo](https://img.shields.io/badge/GitHub-api--media--sosial-181717?style=for-the-badge&logo=github)](https://github.com/razaq-himawan/api-media-sosial)
