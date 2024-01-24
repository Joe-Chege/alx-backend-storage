# alx-backend-storage - Redis Basic

## Overview

This repository contains a set of tasks focused on implementing basic Redis functionality in Python. The tasks are designed to help users learn how to use Redis for various operations, including caching, data storage, and tracking.

## Repository Structure

The repository is organized as follows:

- **Directory:** 0x02-redis_basic
  - **File:** exercise.py
    - Contains the implementation of the Cache class and associated tasks.
  - **File:** web.py (Advanced Task)
    - Contains the implementation of the `get_page` function for an expiring web cache and tracker.

## Task Descriptions

### 0. Redis Basics

#### Learning Objectives:
- Learn how to use Redis for basic operations.
- Learn how to use Redis as a simple cache.

#### Requirements:
- All files interpreted/compiled on Ubuntu 18.04 LTS using Python3 (version 3.7).
- Code should adhere to specific style guidelines (PEP 8).
- Documentation is mandatory for modules, classes, functions, and methods.
- Functions and coroutines must be type-annotated.
- Redis should be installed on Ubuntu 18.04, and the Python Redis client should be installed using `pip3`.

### 1. Reading from Redis and Recovering Original Type

#### Learning Objectives:
- Understand how Redis stores and retrieves data.
- Implement a `get` method to retrieve data with optional type conversion.

### 2. Incrementing Values

#### Learning Objectives:
- Learn about the `INCR` command in Redis.
- Implement a `count_calls` decorator to count the number of times methods are called.

### 3. Storing Lists

#### Learning Objectives:
- Familiarize with Redis list commands (RPUSH, LPUSH, LRANGE).
- Implement a `call_history` decorator to store the history of inputs and outputs for a function.

### 4. Retrieving Lists

#### Learning Objectives:
- Retrieve and display the history of calls for a specific function.
- Use keys generated in previous tasks to generate the desired output.

### 5. Implementing an Expiring Web Cache and Tracker (Advanced)

#### Learning Objectives:
- Implement a `get_page` function to fetch HTML content from a URL.
- Track the number of accesses for a specific URL with an expiration time.
- Bonus: Implement the use case with decorators.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/alx-backend-storage.git
   cd alx-backend-storage/0x02-redis_basic
   ```

2. Install Redis on Ubuntu 18.04:
   ```bash
   sudo apt-get -y install redis-server
   ```

3. Install Python Redis client:
   ```bash
   pip3 install redis
   ```

4. Run the tasks:
   ```bash
   # For each task, execute the associated main.py file
   python3 main.py
   ```

## Additional Notes

- Make sure to follow the provided instructions for each task.
- The advanced task involves implementing a web cache and tracker in a separate file named `web.py`.

**Copyright © 2024 ALX, All rights reserved.**