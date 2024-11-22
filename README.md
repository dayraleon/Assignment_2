# Assignment_2
# Resource Allocation System Simulation

## Overview

This is a simulation of a resource allocation system where multiple processes request, hold, and release resources. The goal of this project is to understand how resource allocation works in operating systems and how deadlock can occur. It simulates a scenario where processes are competing for resources, and if the resources are not available, they wait. If a cyclic waiting situation occurs, it results in a deadlock.

### Intended Audience
This application is intended for:
- **Students** studying operating systems and resource allocation algorithms.
- **Educators** who are teaching operating systems concepts.
- **Software developers** interested in learning about process synchronization, resource management, and deadlock detection.

### Problem Statement
In this simulation, we have a set of processes and resources. Each process requests resources based on its maximum demand, holds the resources while performing some work, and releases them once done. The system can enter a deadlock if processes are waiting indefinitely for resources held by others.

The program implements basic resource allocation logic, handles deadlock detection, and allows for easy visualization of the current system state.

---

## Features

- **Resource Management**: Simulates processes requesting and holding resources with limited units.
- **Deadlock Detection**: A simple algorithm checks for deadlock based on circular waiting.
- **Resource Allocation Logic**: If sufficient resources are available, they are allocated to the requesting process.
- **Process Request & Release**: Processes can request, hold, and release resources as per their needs.
- **Deadlock Reporting**: The system will notify if a deadlock situation occurs where processes are stuck.

---

## How to Run the App

### Prerequisites
- Python 3.6 or higher installed on your machine.

### Steps to Run:
1. **Clone the Repository**:
   git clone https://github.com/dayraleon/Assignment_2.git
