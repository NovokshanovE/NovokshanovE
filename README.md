<div align="center">

# Hi, I'm Evgeny Novokshanov

### Go Backend Engineer · Distributed Systems · System Design

I build backend services, developer tools and systems for analysing complex software architectures.

[![CV](https://img.shields.io/badge/CV-View%20online-2ea44f?style=for-the-badge)](https://novokshanove.github.io/CV/)
[![Certificates](https://img.shields.io/badge/Certificates%20%26%20Diplomas-Repository-blue?style=for-the-badge)](https://github.com/NovokshanovE/Progress)

</div>

## About me

I'm a backend engineer focused on **Go, distributed systems, microservice architecture and high-load applications**.

* Bachelor's degree from **Bauman Moscow State Technical University**, CAD Development
* Master's degree from **ITMO University**, Software for High-Load Systems
* Building **DevArch** — an architecture copilot for designing, validating and evolving microservice systems
* Working with network data processing, BGP, gRPC/HTTP APIs and performance-critical backend services
* Exploring LLM-powered developer tools, local models and multi-agent systems
* Interested in system design, observability, GPU computing and low-level programming

## Current focus

* Designing reliable and maintainable backend services in Go
* Developing architecture analysis and code-generation tools
* Building self-hosted LLM-powered developer tools
* Optimising data processing and distributed-system performance
* Expanding my knowledge of Rust, GPU computing and computer vision

## Featured projects

### Master's thesis — High-performance BGP processing service

A standalone Go service for collecting, processing and distributing BGP routing data.

`Go` `GoBGP` `gRPC` `HTTP` `ART` `Networking`

* Extracted BGP processing from a larger collector into an independent service
* Implemented full routing-table snapshot processing followed by incremental BGP updates
* Designed gRPC and HTTP APIs for downstream services
* Used sharded Adaptive Radix Trees for efficient IP prefix storage and lookup
* Worked on reducing full-view processing time and memory overhead
* Added processing and storage of route-flapping prefixes

[View thesis materials](https://github.com/NovokshanovE/master_thesis)

---

### [LLM Code Review Platform](https://github.com/NovokshanovE/LLM-Code-Review)

A self-hosted platform for reviewing Git branches with OpenAI-compatible language models.

`Go` `MongoDB` `Docker` `React` `REST API` `LLM`

* Runs every review inside an isolated Docker container
* Clones a repository and analyses the complete branch diff against its merge base
* Uses a background worker queue for asynchronous review jobs
* Stores execution logs, review history and Markdown reports
* Supports custom task descriptions and project-specific coding guidelines
* Works with local and corporate OpenAI-compatible model endpoints

---

### [SQL-Opti-Viz](https://github.com/NovokshanovE/SQL-Opti-Viz)

A self-hosted tool for analysing and optimising PostgreSQL queries.

`Go` `PostgreSQL` `React` `Docker` `SQL AST` `EXPLAIN`

* Visualises PostgreSQL execution plans as interactive graphs
* Provides a structured SQL AST explorer
* Detects common performance issues using a rule-based analysis engine
* Supports both direct database connections and fully offline analysis
* Includes a CLI, web interface and single-container deployment
* Keeps database queries and execution plans inside the user's infrastructure

---

### [gRPC Messenger](https://github.com/fatalem0/MHS-Software-Design-25/tree/HW_messenger/messenger-grpc)

A compact messenger backend prototype built with Go, gRPC and Protocol Buffers.

`Go` `gRPC` `Protocol Buffers` `Client–Server Architecture`

* Defines the messenger API through language-independent Protobuf contracts
* Demonstrates communication between independent client and server components
* Separates transport-level gRPC code from application logic
* Explores the design of messaging operations and service boundaries
* Created as a practical software-design assignment

---

### [Unix-like CLI Shell](https://github.com/fatalem0/MHS-Software-Design-25)

A team project implementing a command-line shell in Rust as part of the MHS Software Design course.

`Rust` `CLI` `Process Management` `CI/CD` `Testing`

* Implements built-in versions of `cat`, `echo`, `pwd` and `wc`
* Supports launching external processes
* Handles environment variables and variable substitution
* Supports redirection of `stdin`, `stdout` and `stderr`
* Includes automated tests, coverage tooling and GitHub Actions
* Developed collaboratively with code review and contribution guidelines

---

### [Photogrammetry coursework](https://github.com/NovokshanovE/PhotogrammetryTasks2026)

Practical implementations of classical computer-vision and 3D-reconstruction algorithms.

`C++` `Computer Vision` `SIFT` `SfM` `MVS` `3D Reconstruction`

Course topics and assignments include:

* SIFT keypoint detection and description
* Feature matching and homography estimation
* Camera pose and relative orientation estimation
* Structure from Motion and point-cloud reconstruction
* Bundle Adjustment with Ceres Solver
* Depth-map estimation and PatchMatch
* Multi-View Stereo and surface reconstruction

---

### [GPU Computing coursework](https://github.com/NovokshanovE/GPGPUTasks2025)

Implementations and performance experiments with massively parallel algorithms.

`OpenCL` `CUDA` `C++` `GPU Computing` `Parallel Algorithms`

Course topics and assignments include:

* Coalesced GPU memory access
* Matrix transposition and multiplication
* Local-memory optimisation
* Parallel reductions and prefix sums
* Radix sort and merge sort
* Sparse matrix-vector multiplication
* Performance profiling and kernel optimisation

---

### [System Design case studies](https://github.com/NovokshanovE/system_design_course)

Architecture exercises focused on translating product requirements into scalable backend systems.

`System Design` `Microservices` `High Load` `Architecture`

The repository contains practical case studies covering:

* Functional and non-functional requirements
* Architecture alternatives and trade-offs
* Service boundaries and integration design
* Scalability, reliability and isolation
* CI/CD environments and operational constraints


## Technologies

**Primary language**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square\&logo=go\&logoColor=white)

**Backend and data**

![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square\&logo=mongodb\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square\&logo=redis\&logoColor=white)
![NATS](https://img.shields.io/badge/NATS-27AAE1?style=flat-square\&logo=natsdotio\&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square\&logo=kubernetes\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square\&logo=prometheus\&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square\&logo=grafana\&logoColor=white)

**Also working with**

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square\&logo=rust\&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square\&logo=cplusplus\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![OpenCL](https://img.shields.io/badge/OpenCL-ED1C24?style=flat-square)

## Let's connect

I'm open to discussing:

* Go backend and distributed-system engineering
* System design and architecture tooling
* Developer tools powered by LLMs
* Early-stage technology startups

My CV is available at **[novokshanove.github.io/CV](https://novokshanove.github.io/CV/)**.
