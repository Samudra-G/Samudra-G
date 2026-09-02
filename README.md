# Hi, I'm Samudra Mukhar Goswami 👋

I'm a backend developer interested in building APIs, working with databases, and learning how real systems handle load and failure.

I mostly work with **Go, C#, .NET, Python, PostgreSQL, Redis, Docker, and AWS**.

I'm also interested in **distributed systems and applied ML**.

## What I Work With

* **Backend:** Go, C#, ASP.NET Core, FastAPI, REST, gRPC
* **Databases:** PostgreSQL, Redis, MongoDB
* **Cloud & DevOps:** AWS, Docker, GitHub Actions, Linux, Bash
* **Testing:** xUnit, pytest, Testcontainers, k6
* **ML:** Python, PyTorch, BERT, embeddings

## Projects

### URL Shortener & Analytics Platform

**C#, .NET 10, ASP.NET Core, EF Core, PostgreSQL, Redis**

* Built a URL shortening API with ASP.NET Core Minimal APIs.
* Added custom aliases, collision handling, and Google OAuth.
* Used Redis to collect click events before writing them to PostgreSQL in batches.
* Added caching and rate limiting for API endpoints.
* Added integration tests with xUnit, PostgreSQL, and Testcontainers.

### Gym Management SaaS

**FastAPI, PostgreSQL, Redis, Celery, AWS, Expo**

* Built a backend for managing multiple gyms and their data.
* Used PostgreSQL for tenant-isolated data and Redis + Celery for background tasks.
* Used `pg_trgm` for fuzzy search and BRIN indexes for audit logs.
* Built a Redis rate limiter using Lua and tested it under concurrent load with k6.
* Deployed the application using AWS EC2 and S3.

### Simple Bank API

**Go, PostgreSQL, Redis, AWS ECR**

* Built a banking API with account and transfer operations.
* Used PostgreSQL transactions to keep account and transfer data consistent.
* Added Redis-backed background jobs for asynchronous work.
* Set up GitHub Actions for testing and Docker image deployment to AWS ECR.
* Load tested the API and tracked p99 latency.

### Movie Recommender System

**Next.js, FastAPI, PostgreSQL, Redis, pgvector**

* Built a movie recommendation service using BERT embeddings.
* Used cosine similarity to find similar movies.
* Stored the embeddings in PostgreSQL using `pgvector`.
* Added Redis caching for frequently requested recommendations.
* Exposed the recommendation system through a FastAPI backend.

## Experience

### Splitwizer

**Open Source Contributor | July 2025 - September 2025**

* Improved backend error handling with structured logging and better exception handling.
* Added regression tests to the CI/CD pipeline.
* Built an image upload and processing pipeline with input validation and cloud storage.

## Education

**Heritage Institute of Technology**

B.Tech in Electronics and Communication Engineering
CGPA: 8.32 | 2022 - 2026

Relevant coursework:
Data Structures, Algorithms, Distributed Systems, Operating Systems, Computer Networks

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,cs,dotnet,python,cpp,fastapi,postgres,redis,mongodb,docker,aws,githubactions,linux,bash,kafka,kubernetes,git,github&perline=9" alt="Tech Stack" />
</p>

## Connect

<p align="left">
  <a href="https://www.linkedin.com/in/samudra-goswami/">
    <img src="https://skillicons.dev/icons?i=linkedin" height="40" />
  </a>
  <a href="https://github.com/Samudra-G/">
    <img src="https://skillicons.dev/icons?i=github" height="40" />
  </a>
  <a href="mailto:samudramukhar@gmail.com">
    <img src="https://skillicons.dev/icons?i=gmail" height="40" />
  </a>
</p>
