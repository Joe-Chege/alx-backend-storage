# README.md - NoSQL Project

## Overview

This repository contains a set of tasks related to NoSQL and MongoDB. The project aims to provide practical experience with MongoDB and Python, covering various aspects such as database creation, document insertion, querying, and more.

## Table of Contents

1. [Introduction](#introduction)
2. [Learning Objectives](#learning-objectives)
3. [Project Structure](#project-structure)
4. [Environment Setup](#environment-setup)
5. [Tasks](#tasks)
    - [Task 0: List all databases](#task-0-list-all-databases)
    - [Task 1: Create a database](#task-1-create-a-database)
    - [Task 2: Insert document](#task-2-insert-document)
    - [Task 3: All documents](#task-3-all-documents)
    - [Task 4: All matches](#task-4-all-matches)
    - [Task 5: Count](#task-5-count)
    - [Task 6: Update](#task-6-update)
    - [Task 7: Delete by match](#task-7-delete-by-match)
    - [Task 8: List all documents in Python](#task-8-list-all-documents-in-python)
    - [Task 9: Insert a document in Python](#task-9-insert-a-document-in-python)
    - [Task 10: Change school topics](#task-10-change-school-topics)
    - [Task 11: Where can I learn Python?](#task-11-where-can-i-learn-python)
    - [Task 12: Log stats](#task-12-log-stats)
    - [Task 13: Regex filter](#task-13-regex-filter)
    - [Task 14: Top students](#task-14-top-students)
    - [Task 15: Log stats - new version](#task-15-log-stats---new-version)
6. [Advanced Tasks](#advanced-tasks)
    - [Task 100: Regex filter](#task-100-regex-filter)
    - [Task 101: Top students](#task-101-top-students)
    - [Task 102: Log stats - new version](#task-102-log-stats---new-version)
7. [Resources](#resources)
8. [License](#license)

## Introduction

NoSQL databases have become popular for their flexibility and scalability in handling large volumes of unstructured or semi-structured data. MongoDB, a NoSQL database, is widely used for its document-oriented nature and ease of use.

This project provides hands-on experience with MongoDB, Python, and related technologies. It covers fundamental concepts such as creating databases, inserting documents, querying data, and performing updates.

## Learning Objectives

Upon completion of this project, you should be able to:

- Understand the concept of NoSQL databases.
- Differentiate between SQL and NoSQL databases.
- Comprehend ACID properties in the context of databases.
- Work with document storage in MongoDB.
- Recognize various types of NoSQL databases.
- Realize the benefits of using a NoSQL database.
- Execute queries to retrieve information from a NoSQL database.
- Perform insertion, updating, and deletion of information in a NoSQL database.
- Utilize MongoDB in conjunction with Python.

## Project Structure

The project is organized into tasks, each focusing on a specific aspect of NoSQL and MongoDB. The tasks are designed to be completed sequentially, building on the knowledge gained in earlier tasks. The project structure is as follows:

- **Task 0 to Task 7:** Fundamental MongoDB operations using the mongo shell.
- **Task 8 to Task 15:** Python scripts interacting with MongoDB using PyMongo.
- **Advanced Tasks (Task 100 to Task 102):** More complex scenarios and advanced functionalities.

## Environment Setup

Before starting the tasks, ensure that you have MongoDB installed on your system. Follow the official installation guide for MongoDB [here](https://docs.mongodb.com/manual/installation/).

Additionally, you will need Python 3 and PyMongo. You can install PyMongo using the following:

```bash
$ pip3 install pymongo
```

## Tasks

### Task 0: List all databases

Write a script that lists all databases in MongoDB.

**Example:**
```bash
$ cat 0-list_databases | mongo
```

### Task 1: Create a database

Write a script that creates or uses the database `my_db`.

**Example:**
```bash
$ cat 1-use_or_create_database | mongo
```

### Task 2: Insert document

Write a script that inserts a document in the collection `school`.

**Example:**
```bash
$ cat 2-insert | mongo my_db
```

...

(Continue the pattern for the remaining tasks)

## Advanced Tasks

### Task 100: Regex filter

Write a script that lists all documents with name starting by "Holberton" in the collection `school`.

**Example:**
```bash
$ cat 100-find | mongo my_db
```

### Task 101: Top students

Write a Python function that returns all students sorted by average score.

**Example:**
```bash
$ cat 101-main.py | python3
```

### Task 102: Log stats - new version

Improve `12-log_stats.py` by adding the top 10 of the most present IPs in the collection `nginx` of the database `logs`.

**Example:**
```bash
$ ./102-log_stats.py
```

## Resources

- [NoSQL Databases Explained](https://www.mongodb.com/nosql-explained)
- [What is NoSQL?](https://www.mongodb.com/nosql-explained/nosql-vs-sql)
- [MongoDB with Python Crash Course - Tutorial for Beginners](https://www.youtube.com/watch?v=E-1xI85Zog8)
- [MongoDB Tutorial 2: Insert, Update, Remove, Query](https://www.youtube.com/watch?v=zaCXYpVBz7o)
- [Aggregation](https://docs.mongodb.com/manual/aggregation/)
- [Introduction to MongoDB and Python](https://real