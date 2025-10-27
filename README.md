# Linux Projects Portfolio

A collection of Linux-based projects, scripts, and utilities focused on automation, configuration, and learning.

**Tech Stack:** Bash, Python, C, Linux command-line tools  
**Main Repository:** [github.com/j99973/Linux-Projects](https://github.com/j99973/Linux-Projects)

---

## 🔐 Smart Face Recognition Door Lock System

IoT security system with real-time facial recognition, automated access control, and web-based surveillance dashboard built on Raspberry Pi.

**Tech Stack**
* Python, OpenCV, Flask, Raspberry Pi OS (Linux)
* HTML/CSS/JavaScript, Bootstrap 5, Chart.js
* GPIO hardware control, USB camera integration

**Highlights**
* Real-time facial recognition with 95%+ accuracy using LBPH algorithm and <100ms unlock latency
* RESTful API with 15 endpoints for authentication, surveillance, and door control operations
* Responsive web dashboard with live MJPEG video streaming (30 FPS) and analytics
* Automated surveillance system with perceptual hashing for duplicate detection (90% reduction in false captures)
* Multi-threaded architecture optimized for embedded systems (60% CPU usage)
* GPIO-controlled solenoid lock mechanism with fail-safe state management
* Handles 100+ authorized users with complete audit trail and activity logging

**[View Project →](https://github.com/j99973/face-recognition-door-lock)**

---

## ⚙️ Ansible Infrastructure Automation Project

A comprehensive automation project using Ansible to configure Linux systems for dev, enrollment, and monitoring environments. It uses modular roles, systemd integration, and Prometheus for observability.

**Tech Stack**
* Ansible, YAML, Jinja2, systemd

**Highlights**
* Automates provisioning of dev, enrollment, and monitoring hosts
* Deploys Prometheus and Node Exporter with templated configs
* Uses Jinja2 for dynamic file generation and role-based deployment
* Runs services using `.service` files under systemd

**[View Project →](https://github.com/j99973/ansible-infrastructure)**

---

## 🚀 NASA APOD Newsletter Generator

A Python-based utility that pulls random space images and metadata from NASA's APOD API, then renders a styled HTML newsletter using Jinja2 templates.

**Tech Stack**
* Python, Jinja2, HTML/CSS

**Highlights**
* Fetches 3 random astronomy photos from NASA's API
* Downloads and organizes images in a build directory
* Renders an HTML newsletter with image descriptions and titles

**[View Project →](https://github.com/j99973/nasa-apod-newsletter)**

---

## 🎯 Bash Quiz Script

An interactive terminal quiz game using Bash that tests knowledge of Linux, Bash, and Python concepts through `.txt` files and randomized questions.

**Tech Stack**
* Bash

**Highlights**
* Pulls multiple-choice questions from structured text files
* Tracks answers and gives a percentage-based performance report

**[View Project →](https://github.com/j99973/bash-quiz)**

---

## 📊 Linux Logging Project

A set of Bash, Python, and C tools designed to automate system logging, monitor activity, and generate reports for Linux environments.

**Tech Stack**
* Bash, Python, C

**Highlights**
* Automation scripts for system monitoring and log analysis
* Custom CLI tools for log parsing and reporting
* Security and audit log utilities

**[View Project →](https://github.com/j99973/linux-logging)**

---

## ✅ Config Checker Script

A lightweight Bash tool that reads `.info` files and verifies the existence, structure, and content of listed configuration files within a selected directory.

**Tech Stack**
* Bash

**Highlights**
* Automatically detects config folders and parses `.info` metadata
* Flags missing or misconfigured files for review

**[View Project →](https://github.com/j99973/config-checker)**

---
