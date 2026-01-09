# Docker Learning With MERN Docker Project

A hands-on repository where I learned Docker from scratch and applied it to real projects, including Dockerizing a MERN stack application.

This repo contains:

* Docker basics with explanations and examples
* Dockerfiles for different services
* Docker Compose setups
* A working **MERN project** containerized with Docker

This reflects everything I practiced while mastering Docker and applying it to full-stack development.

---

## 🧠 What This Project Covers

### Docker Fundamentals

You’ll find step-by-step learning material and working files for:

* Images vs Containers
* Building images with **Dockerfile**
* Running containers locally
* Working with volumes and ports
* Environment variables
* Best practices in Dockerfile writing

Everything is structured so you can pick up Docker even if you started from zero.

### MERN Project with Docker

This repo also contains a complete **MERN stack project** that is:

* Fully containerized
* Run using **docker compose**
* Configured so services (backend, frontend, database) work together

This is important because Docker shines when a system has multiple services that need to be networked, started together, and managed as a group.

---

## 📁 Repo Structure

```
/
├── basics/
│   ├── Dockerfile-examples/
│   ├── commands.txt
│   └── notes.md
├── mern_project/
│   ├── backend/
│   ├── frontend/
│   ├── .env.example
│   ├── docker-compose.yml
│   ├── Dockerfile (for each service)
│   └── README-mern.md
└── README.md
```

* **basics/** – Core Docker concepts with examples
* **mern_project/** – A full MERN app containerized with Docker

---

## 🚀 How to Use This Repo

### 1) Docker Basics

Go into the `basics/` folder. You’ll find:

* Simple Dockerfiles
* Commands you can copy and run
* Notes explaining each command

These help you learn how Docker builds, runs, and manages containers.

### 2) MERN App

Here’s how to get the full MERN stack running:

1. Clone this repo

   ```
   git clone https://github.com/Saurabh-Shivam/Docker.git
   ```

2. Go to the MERN project folder

   ```
   cd Docker/mern_project
   ```

3. Make a copy of the environment file and fill in your values

   ```
   cp .env.example .env
   ```

4. Build and run all services with Docker Compose

   ```
   docker compose up --build
   ```

That one command sets up:

* MongoDB
* Backend API
* Frontend UI

It networks them together automatically, without separate `docker run` commands. ([GitHub][1])

---

## 🧩 What You’ll Learn By Exploring This Repo

### Dockerfile Skills

* Writing efficient Dockerfiles
* Multi-stage builds
* Managing dependencies

### Docker Compose Skills

You’ll see why **docker-compose.yml** matters. It lets you:

* define multiple services
* set environment variables
* manage volumes
* control startup order

A Dockerfile builds one image — Compose runs an entire system. ([FreeCodeCamp][2])

### Real-World Deployment Prep

By the time you finish this repo you’ll know how to:

* Dockerize real applications
* Run clustered services
* Prepare apps for production or CI/CD

---

## 💡 Tips

* Explore the basics first before jumping into the MERN project
* Read the comments in each Dockerfile — they explain what’s happening
* Try modifying and rebuilding containers to deepen your understanding

---

[1]: https://github.com/banesullivan/README?utm_source=chatgpt.com "How to write a good README"
[2]: https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/?utm_source=chatgpt.com "How to Write a Good README File for Your GitHub Project"
