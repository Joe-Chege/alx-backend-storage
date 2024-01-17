Sure, here is a detailed README.md file for the given task:

# Task Project: MySQL Advanced

## Overview

This project focuses on advanced MySQL concepts, including creating tables with constraints, optimizing queries, implementing stored procedures, triggers, and views in MySQL. The tasks cover a range of operations, from basic table creation to more complex features like indexing and stored procedures.

## Concepts Explored

- **Advanced SQL**: Understanding and implementing advanced SQL concepts.
- **MySQL Cheatsheet**: Utilizing MySQL commands and syntax.
- **Database Indexing**: Leveraging indexing to optimize query performance.
- **Stored Procedures**: Creating and implementing stored procedures in MySQL.
- **Triggers**: Understanding and implementing triggers in MySQL.
- **Views**: Creating and utilizing views in MySQL.

## Project Structure

The project is organized into several tasks, each focusing on a specific aspect of MySQL advanced concepts. Below is an overview of each task:

### Task 0: We are all unique!

- **Objective**: Create a table 'users' with specified attributes and enforce uniqueness.
- **File**: 0-uniq_users.sql

### Task 1: In and not out

- **Objective**: Create a table 'users' with additional country attribute and default values.
- **File**: 1-country_users.sql

### Task 2: Best band ever!

- **Objective**: Rank country origins of bands based on the number of fans.
- **File**: 2-fans.sql

### Task 3: Old school band

- **Objective**: List bands with Glam rock as their main style, ranked by longevity.
- **File**: 3-glam_rock.sql

### Task 4: Buy buy buy

- **Objective**: Create a trigger to decrease the quantity of an item after adding a new order.
- **Files**: 4-init.sql, 4-store.sql, 4-main.sql

### Task 5: Email validation to sent

- **Objective**: Create a trigger to reset 'valid_email' attribute only when the email has been changed.
- **Files**: 5-init.sql, 5-valid_email.sql, 5-main.sql

### Task 6: Add bonus

- **Objective**: Create a stored procedure 'AddBonus' for adding a new correction for a student.
- **Files**: 6-init.sql, 6-bonus.sql, 6-main.sql

### Task 7: Average score

- **Objective**: Create a stored procedure 'ComputeAverageScoreForUser' to compute and store the average score for a student.
- **Files**: 7-init.sql, 7-average_score.sql, 7-main.sql

### Task 8: Optimize simple search

- **Objective**: Create an index 'idx_name_first' on the 'names' table for the first letter of the name.
- **File**: 8-index_my_names.sql

### Task 9: Optimize search and score

- **Objective**: Create an index 'idx_name_first_score' on the 'names' table for the first letter of the name and the score.
- **File**: 9-index_name_score.sql

### Task 10: Safe divide

- **Objective**: Create a function 'SafeDiv' for safe division, handling division by zero.
- **File**: 10-div.sql

### Task 11: No table for a meeting

- **Objective**: Create a view 'need_meeting' listing students with scores under 80 and no last meeting or more than 1 month.
- **Files**: 11-init.sql, 11-need_meeting.sql, 11-main.sql

## Getting Started

Follow the steps below to complete and test each task:

1. Execute the SQL scripts in the provided order for each task.
2. Use the provided sample commands or modify them based on your requirements.
3. Check the results and validate against the expected outcomes.

## Additional Information

- **Environment**: Ubuntu 18.04 LTS using MySQL 5.7
- **Tools**: Use "container-on-demand" to run MySQL.
- **Comments**: Follow the specified commenting guidelines for SQL files.

## Conclusion

By completing this project, you'll gain a solid understanding of advanced MySQL concepts, enhancing your skills in database management and optimization.
