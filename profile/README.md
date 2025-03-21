#   The Capstone Project: LINUX DISTRIBUTION FOR AI/ML APPLICATIONS
https://cse-capstoneproject.pages.dev/

##   Overview

This repository contains the code and documentation for the Capstone Project, an AI/ML focused initiative developed by the Department of Computer Science and Engineering at Muthoot Institute of Technology & Science. This project centers around a Linux distribution and includes several supporting tools.

##   Main Project Components

* **Linux Distribution for AI/ML Applications:**

    * The core of this project is a Linux kernel designed to provide an environment for AI/ML development and deployment.
    * It is based on Debian.
* **Clearch:**

    * Clearch is a command-line search engine utilizing various AI models, including Gemini, Rust, and GPT.
    * These models are structured as Rust modules.
    * Each AI model implements the `LLMRequest` trait.

##   Supporting Components

* **OS Scraper:**

    * This component is designed to reduce time complexity for the RAG Agent to retrieve data.
    * It uses multiple agents built with Go.
* **RAG Agent:**

    * The RAG agent combines retrieval-based search with generative AI models.
    * This enhances the accuracy and reliability of AI-generated content by grounding responses in authoritative data sources.
* **Peaploy:**

    * Peaploy is Rust-based.
    * It uses the `tree-sitter` library to parse code and analyze import, system, and build dependencies.
    * It makes use of the `Walkdir` and standard libraries in Rust to read all the files from a project folder, to analyze its dependencies.
* **Spellchecker Tool:**

    * This application demonstrates the use of data structures and algorithms for spell checking.
    * It is built using Go.

##   Technologies Used

* Go
* Rust
* tree-sitter
* Gemini
* GPT
* Walkdir (Rust library)
* Standard libraries (Rust)
* Debian Linux

##   Team

    The project was developed by a team of students from the Department of Computer Science and Engineering:

* Advaith Narayanan (S8 CSE)
* Amalendu P (S8 CSE)
* Andrew C Anil (S6 CY)
* Vaishakh S Nair (S6 CY)
* Alan Mathew (S6 CY)
* Eric Thomas (S6 CSE)
* Athul Prakash (S4 CY)
* Chris Paul (S4 CY)
* Amalekh Biju (S4 CY)
* Sudheesh S Pai (S4 CY)
* Abin Joy (S4 CY)
* Aditi Asok (S4 CY)
* Hafeez Mohamed (S4 CY)
* Anubind C Biju (S4 CY)
* Krishna Rajeev (S4 CY)
* Adithyan Raj (S4 CSE)
* Akshhay K Murali (S4 CSE)

##   Project Timeline and Workflow

* The project timeline and workflow details can be found at [MITS CSE Capstone Project · GitHub](https://github.com/MITSCSECapstoneProject).

##   Project Significance

    This project aims to:

* Develop an AI/ML focused Linux distribution to provide an optimized environment for AI/ML development and deployment.
* Create supporting tools that enhance AI/ML workflows, such as intelligent search capabilities.
* Showcase the integration of AI/ML technologies within system-level software.

##   Social Relevance

    This project aims to:

* Enhance productivity by automating complex tasks.
* Make AI/ML technologies more accessible to developers and users.
* Contribute to advancements in intelligent systems and automation.

##   Roadmap

* **March 2025:** Integrate OS with Kernel
* **June 2025:** Integrate tools with Operating System
* **September 2025:** Release of the OS

##   Getting Started

    To get started with the project, follow these steps:

    1.  Clone the repository: `git clone [repository URL]`  **(Replace `[repository URL]` with the actual repository URL)**
    2.  **Clearch:**

        * Navigate to the `clearch` directory.
        * Ensure you have Rust installed.
        * Use `cargo build` to build the project.
        * Run the executable.
    
    3.  **OS Scraper:**

        * Navigate to the `os-scraper` directory.
        * Ensure you have Go installed.
        * Run `go run main.go` to start the scraper.
    
    4.  **RAG Agent:**
    
    5.  **Peaploy:**

        * Navigate to the `peaploy` directory.
        * Ensure you have Rust installed.
        * Use `cargo build` to build the project.
        * Run the executable with `cargo run [project_folder_path]` (Replace `[project_folder_path]` with the path to the project you want to analyze).
    6.  **Spellchecker Tool:**

        * Navigate to the `spellchecker` directory.
        * Ensure you have Go installed.
        * Run `go run main.go` to start the spellchecker.

