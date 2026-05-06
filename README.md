# HDFS Virtual Laboratory Platform (Showcase)

## Overview
The HDFS Virtual Laboratory Platform is a web-based educational system designed to simulate the core functionalities of the Hadoop Distributed File System (HDFS).  

It allows students to perform distributed system experiments in a fully browser-based environment without requiring Hadoop installation or complex setup.

This project focuses on providing an interactive, academic-grade simulation of HDFS architecture, workflows, and fault tolerance mechanisms.

---

## Key Features

### 1. Browser-Based Lab Environment
- No local installation required
- Fully accessible through web browser
- Cross-platform support

### 2. Experiment Management System
- Structured lab experiments aligned with academic syllabus
- Step-by-step procedures for each experiment
- Sample datasets and expected outputs
- Progress tracking

### 3. Automatic Environment Provisioning
- On-demand environment creation per experiment
- Simulated NameNode and DataNode setup
- Pre-configured datasets and directories
- Zero manual configuration required

### 4. HDFS Simulation Engine
- Block-based file storage simulation
- File splitting and replication logic
- Metadata management via NameNode
- DataNode health monitoring

### 5. Web-Based CLI Interface
Supports realistic HDFS commands:
- `hdfs dfs -ls`
- `hdfs dfs -put`
- `hdfs dfs -get`
- `hdfs dfs -rm`
- `hdfs dfs -mkdir`

Includes:
- Real-time output
- Command history
- Error simulation (Hadoop-like)

### 6. Visualization System
- NameNode and DataNode architecture display
- Block distribution visualization
- Replication flow animation
- File-to-block mapping

### 7. Fault Tolerance Simulation
- Simulated DataNode failure
- Automatic re-replication
- Metadata updates
- Recovery visualization

---

## System Architecture

The platform follows a cloud-based architecture:

User → Web UI (React) → Backend Logic → Firestore Database

### Tech Stack
- Frontend: React
- Backend: Firebase Cloud Functions
- Database: Firestore
- Authentication: Firebase Auth
- Hosting: Firebase Hosting

---

## Educational Use Cases

This platform enables students to:
- Understand HDFS internal architecture
- Visualize distributed storage systems
- Execute HDFS commands safely
- Learn fault tolerance mechanisms
- Perform Big Data experiments interactively

---

## Experiments Included
The system supports multiple Big Data lab experiments, including:
- HDFS command execution
- MapReduce (Word Count)
- Hive operations
- PySpark transformations
- MLlib algorithms
- Data visualization (Matplotlib, Seaborn)
- Streaming with Kafka + Spark

---

## My Contribution

- Designed and structured the platform workflow
- Defined system architecture and experiment modules
- Configured and validated simulation logic
- Improved user interaction and UI flow
- Tested system behavior and experiment outputs

---

## Development Note

This project was developed using AI-assisted tools (e.g., Medo / Firebase Studio).  

Due to platform restrictions, the source code cannot be shared.  

However, the system design, workflow, and implementation logic were actively configured, tested, and refined by me.

---

## Screenshots / Demo

(Add your images here)
