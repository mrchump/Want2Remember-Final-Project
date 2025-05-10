# Want2Remember — CS 3338 Final Project

Want2Remember is a simple, front-end web application designed to help users store, view, and delete short memory entries. It uses browser-based localStorage to persist data between sessions and is fully responsive for both desktop and mobile browsers.

Final project by Kevin Bayona-Galindo and Nikolazi Tartinsky.

---

## Project Overview

This project was completed as the final assignment for CS 3338. It demonstrates practical understanding of key software development tools and workflows including GitHub, Jira, TestRail, Docker, and LaTeX.

The goal was to recreate a simplified version of a senior design project using only front-end technologies. The focus was on documenting each phase of the project lifecycle through snapshot deliverables and maintaining clarity and traceability using the required tools.

---

## Jira Link

Project tasks, sprint planning, and bug tracking were managed through Jira:

https://cs3338group6.atlassian.net/jira/software/projects/W2R/boards/39

---

## Project Objectives

- Design and build a browser-based memory tracking app
- Store memory entries (title and note) in browser localStorage
- Display and delete memory entries with real-time UI updates
- Track tasks using Jira and test features using TestRail
- Document progress and planning through snapshot objectives and LaTeX reports
- Package and deploy the app using Docker and NGINX

---

## Why This Project Was Built

The project is meant to demonstrate front-end development skills, tool integration, and full-cycle documentation. It shows that even a simple app can benefit from proper software design, requirement specification, containerization, and agile workflows.

---

## How to Run the Project

### Option 1: Run Locally

1. Clone the repository:
   ```
   git clone https://github.com/kbthepioneer/Want2Remember-Final-Project.git
   ```
2. Open the `index.html` file in any web browser.

### Option 2: Run Using Docker

1. Make sure Docker Desktop is running
2. In the project directory, run:
   ```
   docker-compose up
   ```
3. Open a browser and visit:
   ```
   http://localhost:8080
   ```

---

## Project Deliverables

- `SDD_FINAL.tex` – Software Design Document
- `SRS_FINAL.tex` – Software Requirements Specification
- `design_spec_FINAL.tex` – Design Spec with architecture, tools, and deployment info
- `user_manual_FINAL.tex` – User Manual and project overview
- `snapshot_objectives_LaTeX.tex` – Summary of all snapshot objectives
- Snapshot 1–4 folders – Contain objectives and reflections for each phase
- TestRail Reports – PDF exports of tests from Snapshots 2–4
- `workflow_diagram_FINAL.png` – High-level visual overview of the app
- `system_architecture_FINAL.png` – System architecture showing data and structure
- `docker-compose.yml` – Docker container config using NGINX

---

## Technologies Used

- HTML, CSS, JavaScript
- localStorage (no backend required)
- GitHub (version control)
- Jira (task management and sprint tracking)
- TestRail (test case and run management)
- LaTeX (technical documentation)
- Docker + NGINX (deployment)
