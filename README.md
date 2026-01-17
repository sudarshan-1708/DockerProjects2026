# 📦 DockerProject2026

## Docker Hands-On Projects: From Single Container to Swarm & Stack

This repository contains a **progressive set of Docker projects** designed to demonstrate **real-world containerization and orchestration skills** — starting from a single-container application and evolving into **multi-container**, **Docker Compose**, **Docker Swarm**, and **Docker Stack** deployments.

Each project builds on the previous one, mirroring how applications grow in **real production environments**.

---

## 🎯 Objectives

- Develop a strong understanding of Docker architecture
- Build production-quality Docker images
- Design and run multi-container applications
- Apply container networking and persistent storage concepts
- Deploy and manage applications using Docker Compose and Docker Swarm
- Understand orchestration concepts such as scaling, rolling updates, and fault tolerance

---

## 🧩 Project Overview

### 🟢 Project 01: Single Container Application
**Goal:**  
Containerize a minimal web application using a production-grade Dockerfile.

**Key Concepts:**
- Dockerfile best practices
- Image layering and cache behavior
- Environment variables
- Container lifecycle and logging

📂 Folder: `01-single-container-app`

---

### 🟡 Project 02: Multi-Container Application
**Goal:**  
Develop and run a multi-service application where containers communicate over Docker networks and persist data using volumes.

**Key Concepts:**
- User-defined bridge networks
- Container DNS and service discovery
- Volumes and persistent data
- Service isolation and dependency handling

📂 Folder: `02-multi-container-app`

---

### 🔵 Project 03: Docker Swarm Deployment
**Goal:**  
Deploy the application as a distributed system using Docker Swarm with multiple replicas and high availability.

**Key Concepts:**
- Docker Swarm architecture (manager and worker nodes)
- Services vs containers
- Scaling and rolling updates
- Internal load balancing
- Basic Swarm security practices

📂 Folder: `03-docker-swarm`

---

### 🟣 Project 04: Docker Compose to Docker Stack
**Goal:**  
Transition from local development using Docker Compose to a production-style deployment using Docker Stack on Swarm.

**Key Concepts:**
- Docker Compose vs Docker Stack
- Environment separation (development vs production)
- Stack deployment
- Production-ready service definitions

📂 Folder: `04-compose-to-stack`

---

## 🛠️ Tech Stack

- Docker Engine
- Docker Compose
- Docker Swarm
- Linux Containers
- Minimal Web Application (language/framework chosen per project)

---

## 📌 How to Use This Repository

Each project directory contains a dedicated `README.md` with:
- Problem statement
- Architecture overview
- Concepts used
- Execution instructions
- Key learnings and reflections

Projects are **independent but progressive** — it is recommended to start with Project 01 and move sequentially.

---

## 📈 Why This Repository Exists

This repository was created as a **hands-on learning and evaluation exercise** to move beyond theoretical Docker knowledge and apply containerization concepts in **practical, production-like scenarios**.

---

## 👤 Author

**Harry H**  
Software Engineer | Cloud & DevOps Enthusiast

---

## 📝 Notes

- This repository focuses on **learning by building**, not just running examples.
- Design decisions and trade-offs are documented in each project.
- Evaluation and iteration are part of the learning process.
