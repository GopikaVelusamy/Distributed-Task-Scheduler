# Distributed-Task-Scheduler
This project implements a Directed Acyclic Graph (DAG) based workflow orchestration system that allows users to define, validate, and execute task dependencies efficiently. It ensures correctness through cycle detection and provides a structured backend API with an interactive frontend for managing workflows.

# Features
Define tasks and dependencies as a Directed Acyclic Graph (DAG)
Automatic cycle detection to prevent invalid workflows
Execution of tasks in dependency order
RESTful API using FastAPI
Interactive frontend interface
Modular and scalable project structure
Dockerized setup for easy deployment

# System Workflow
Users create tasks and define dependencies between them.
The system represents these dependencies as a Directed Acyclic Graph (DAG).
A cycle detection algorithm validates the graph structure.
If valid, tasks are executed in the correct topological order.
