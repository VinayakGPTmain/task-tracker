# Task Tracker — Project Vision & Documentation

## 1. Vision Document

### Problem Statement
Modern professionals and students struggle with scattered tasks across non-persistent or overly complex project management tools. Existing solutions often carry heavy overhead, require account creation, or lack offline resiliency. The **Task Tracker App** provides a lightweight, zero-overhead, privacy-first task management tool served locally via lightweight containerized infrastructure.

### Target Personas
* **Devin (Software Developer):** Needs a quick, keyboard-driven tool to manage daily task lists without navigating heavy enterprise web applications.
* **Priya (Engineering Student):** Requires a reliable, distraction-free interface to track assignment deadlines that persists state locally across browser reloads.

### Vision Statement
"To provide a seamless, high-performance, containerized task management experience that balances raw functional efficiency with local-first data privacy."

### Key Features & Value Proposition
* **Zero Latency & Local Persistence:** Fast CRUD operations backed by browser LocalStorage.
* **Granular Organization:** Due dates, priority levels (High/Medium/Low), and category tagging.
* **Dynamic Search & Filtering:** Live search filtering alongside status tabs (All / Active / Completed).
* **Containerized Deployment:** Powered by lightweight Nginx on Docker Alpine for consistent cross-platform execution.

### Success Metrics
* 100% functional coverage across all 25 mapped user stories.
* Sub-100ms UI interaction responsiveness.
* Zero external backend dependencies for core operations.

---

## 2. Technical Architecture & Setup

### Tech Stack
* **Frontend:** HTML5, CSS3, Modern JavaScript (ES6+)
* **Container Layer:** Docker, Nginx (Alpine Linux distribution)
* **Version Control & Management:** Git, GitHub Flow, GitHub Projects (Kanban)

### Local Development Setup

#### Prerequisites
* Docker Desktop installed and running
* Git installed

#### Execution Instructions
1. Clone the repository:
   ```bash
   git clone [https://github.com/VinayakGPTmain/task-tracker.git](https://github.com/VinayakGPTmain/task-tracker.git)
   cd task-tracker
