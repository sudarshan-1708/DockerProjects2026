# Single Container Application

🟢 **Assignment 1: Single Container Application (Foundation)**

**Goal:** Learn how a real application becomes a container — from source code to a running service — with correct Docker fundamentals.

## 🧠 Scenario

You are building the first version of a minimal web application.

At this stage:
* No database
* No backend services
* No external dependencies
* Everything runs inside one container

This version exists only to validate containerization fundamentals.

## 📦 What You Need to Build

A minimal web application that:
* Serves a simple UI page
* Stores values in memory only (variables)
* Exposes at least one HTTP endpoint
* Reads configuration from environment variables
* Logs requests to stdout

You can use any language/framework you are comfortable with.

## 🧩 Concepts You Are Learning

* Docker architecture (client–daemon)
* Dockerfile fundamentals
* Image layering & cache behavior
* Build context understanding
* Container lifecycle
* Environment variable injection
* Container logging (stdout/stderr)
* Port exposure vs publishing

## 🛠️ Tasks (What to Do — Not How)

* Design a minimal UI page
* Implement a basic web server
* Containerize the application using a production-quality Dockerfile
* Build the image and observe:
   * Layer creation
   * Cache reuse
* Run the container with:
   * Custom environment variables
   * Port mapping
* Stop and restart the container cleanly

## ✅ Success Criteria (How You Know You're Done)

* The application runs only inside a container
* No runtime dependency exists on the host
* Environment variables change app behavior without rebuilding
* Logs are visible using Docker commands
* Container stops gracefully (no forced kill)

## 💡 Hints (Guidance Without Spoilers)

Use these to stay on the right path, not as instructions:

* Prefer official base images
* Keep your Dockerfile:
   * Readable
   * Ordered for cache efficiency
* Assume the container:
   * Can be stopped anytime
   * Can be recreated anytime
* Avoid:
   * Writing logs to files
   * Hardcoding configuration values
* Think:
   * "If I rebuild, what should invalidate cache?"
   * "If I restart, what should reset?"


## 🔍 Reflection Questions (Answer After Completion)

* Why did you choose this base image?
* Which Dockerfile instruction breaks cache most often?
* What would change if this went to production?


## 🧭 Ground Rules (Important)

* ❌ No Docker Compose yet
* ❌ No database
* ❌ No Swarm
* ❌ No orchestration
* ✅ Single container only