# Warehouse Management System 

## Overview
This project is a command-line simulation of a warehouse management system, developed in C++. It processes orders, manages various types of volunteers (collectors and drivers with specific limitations), and serves different customer profiles (soldiers and civilians). The simulation is advanced step-by-step through a custom action loop, maintaining the exact state of all entities.

## Technical Highlights
* **Object-Oriented Design:** Extensive use of inheritance and polymorphism to represent distinct warehouse entities and handle complex action requests seamlessly.
* **Memory Management:** Implements strict manual memory management using raw pointers. The central `WareHouse` class fully implements the **Rule of 5** (Copy/Move constructors, Copy/Move assignment operators, Destructor) to ensure safe resource handling and zero memory leaks.
* **Data Structures:** Utilizes standard C++ containers like `std::vector` for efficient entity tracking, history logging, and state management.

## Getting Started

### Prerequisites
* A UNIX-based environment
* `g++` compiler with C++11 support
* `make`

### Compilation & Execution
1. Clone the repository and navigate to the project directory.
2. Compile the project using the provided makefile:
   ```bash
   make
   ```
3. Run the executable with a configuration file:
   ```bash
   ./bin/warehouse <path_to_config_file>
   ```
