# 🎵 Centralized Music Control System

## 📌 Overview

Centralized Music Control System is an enterprise multi-branch audio automation platform that allows administrators to control music across multiple zones from a single dashboard.

---

## 🎯 Objectives

* Control music playback centrally
* Manage multiple zones
* Create and schedule playlists
* Provide real-time control
* Role based access

---

## 🧩 Modules

### 1️⃣ Backend API

* Node.js + Express
* REST API
* JWT Authentication
* Socket.io realtime communication

### 2️⃣ Admin Panel

* React dashboard
* Zone monitoring
* Playlist control
* User management

### 3️⃣ Client Service

* Windows service to receive commands
* Auto music playback
* Volume control

### 4️⃣ Database

* MongoDB

---

## ⚙️ Core Features

### 🎵 Music Control

* Play / Pause / Stop
* Next / Previous
* Master volume
* Zone volume

### 🏢 Zone Management

* Add / Edit / Delete zones
* Assign devices

### 📂 Playlist

* Upload songs
* Create playlist
* Schedule playback

### 👤 User Roles

* Admin
* Operator

---

## 🧠 Tech Stack

Backend → Node.js + Express
Frontend → React
Database → MongoDB
Realtime → Socket.io
Auth → JWT
Deployment → Docker

---

## 📡 API Endpoints

### Auth

POST /api/auth/login
POST /api/auth/register

### Zones

GET /api/zones
POST /api/zones
PUT /api/zones/:id
DELETE /api/zones/:id

### Music

POST /api/music/play
POST /api/music/pause
POST /api/music/volume

### Playlist

GET /api/playlists
POST /api/playlists

---

## 🗂️ Folder Structure

/backend
/frontend
/client-service
/database
/docker

---

## 🔐 Non Functional Requirements

* Secure authentication
* Realtime response
* Scalable architecture
* Responsive UI

---

## 🚀 AI CODE GENERATION PROMPT

Create a complete production ready full stack application called Centralized Music Control System.

Requirements:

* Node.js Express backend
* React frontend
* MongoDB database
* Socket.io realtime
* JWT authentication
* Admin dashboard
* Windows client service
* REST API
* Docker support

Generate full folder structure, production ready code, documentation and setup guide.
