---
title: Chat App API
publishDate: 2024-12-25 00:00:00
img: /assets/works/chat-app-api.png
img_alt: Code snippet of the Chat App API
description: |
  A backend API for a simple real-time chat application, built with Go, PostgreSQL, WebSockets, and JWT authentication.
tags:
  - Go
  - API
  - WebSocket
  - PostgreSQL
  - JWT
isFeatured: true
---

This project is a backend API for a **real-time chat application**. It handles user registration, login, and real-time messaging using WebSockets, with secure JWT-based authentication. The server is built with **Go** and uses **PostgreSQL** as its database.

The API is designed with scalability and clean architecture in mind, using modular packages for users, messages, and WebSocket connections.

### 🚀 Features

- 👤 User registration and authentication (JWT)
- 💬 Real-time messaging with WebSockets
- 📦 PostgreSQL as database with `pgx`
- 🌐 CORS support with `chi/cors`
- ✅ Input validation with `validator`

### 🛠 Built With

- **Go** – backend language
- **Chi Router** – lightweight HTTP routing
- **WebSockets** – real-time communication
- **PostgreSQL (pgx)** – database

### 📚 What I Learned

- Structuring a modular Go project with `internal/` packages
- Implementing real-time WebSocket communication in Go
- Securing endpoints with JWT authentication
- Writing APIs with Chi and handling middleware (CORS, validation, auth)

### 🔗 Links

[![GitHub Repo](https://img.shields.io/badge/GitHub-chat--app--api-181717?style=for-the-badge&logo=github)](https://github.com/razaq-himawan/chat-app-api)
