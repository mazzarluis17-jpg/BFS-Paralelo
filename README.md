# Parallel BFS

Performance Comparison Between Sequential and Parallel Breadth-First Search

## Overview

This project compares a traditional sequential Breadth-First Search (BFS) implementation against a parallel BFS implementation developed in Java.

The goal is to evaluate the performance gains obtained through concurrent programming techniques and to measure speedup according to Amdahl's Law.

A web-based interface allows users to configure experiments and visualize results.

## Features

* Sequential BFS implementation
* Parallel BFS implementation
* Multi-threaded execution using ExecutorService
* ConcurrentHashMap synchronization
* JSON API using Undertow
* Interactive web interface
* Performance benchmarking

## Technologies

* Java
* Maven
* Undertow
* Gson
* ExecutorService
* ConcurrentHashMap

## How to Run

Compile the project:

```bash
mvn clean compile
```

Start the server:

```bash
mvn exec:java
```

Open the application:

```text
http://localhost:8080/prueba.html
```

## Experimental Results

The project demonstrates significant speedup when processing large graphs.

Key observations:

* Correctness validated against sequential BFS
* Speedup increases with graph size
* Maximum observed speedup: 21.74x
* Parallel overhead dominates for very small graphs

## Repository Structure

├── src/
├── docs/
├── resources/
└── README.md

## Author

Luis Alfredo Ramírez Maza
