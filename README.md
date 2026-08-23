# TaskTracker

## Overview & Vision Document

### Project Overview
TaskTracker is a minimal web application designed to help students organize daily assignments and track study progress without clutter.

### Problem Statement
Students struggle to keep track of multiple deadlines across different platforms, leading to missed assignments and stress.

### Target Personas
- **Primary Persona:** vinayak, a college student balancing 5 classes and extracurriculars who needs a simple 1-click task logger.

### Vision Statement
To become the friction-free task management tool for students who want clear daily priorities without setup complexity.

### Key Features & Goals
- User authentication (sign up / log in).
- Create, edit, toggle, and delete daily tasks.
- Categorize tasks by subject or priority.

### Success Metrics
- 80% task completion rate for active users.
- Sub-100ms response time for adding/updating tasks.

### Assumptions & Constraints
- Users have basic browser access and an internet connection.
- Built within free-tier deployment limits (e.g., local Docker container / static hosting).

---

## Branching Strategy
We follow **GitHub Flow**:
- `main`: Production-ready code.
- `feature/*`: Short-lived feature branches created from `main` (e.g., `feature/docker-setup`).
- Pull Requests (PRs) are reviewed and merged into `main`.

---

## Local Development Tools
- **Code Editor:** VS Code
- **Containerization:** Docker Desktop
- **Version Control:** Git & GitHub

---

## Quick Start – Local Development

### Prerequisites
- Install [Docker Desktop](https://www.docker.com/products/docker-desktop/) and ensure it is running.

### Running locally with Docker

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/task-tracker.git](https://github.com/YOUR_USERNAME/task-tracker.git)
   cd task-tracker

