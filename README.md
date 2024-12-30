# Game Rental System

This project implements a comprehensive game rental system using PostgreSQL for database management and Java for the user interface. The system includes functionalities for user management, game catalog management, rental order processing, and tracking information.

## Key Features
- **User Management**: Register, login, and update user profiles.
- **Game Catalog**: Browse and filter games by genre and price.
- **Rental Orders**: Place, view, and manage rental orders.
- **Tracking**: Track orders and update their statuses.


## Prerequisites

- Java Development Kit (JDK)
- PostgreSQL
- JDBC Driver for PostgreSQL

## Instructions to Compile and Run the Program

1. **Start PostgreSQL**
    - **If on CS166 PSQL Server:**
      ```bash
      cs166_db_stop
      cs166_db_start
      cs166_db_status
      cs166_createdb <netid>_project_phase_3_DB
      ```

2. **Run the `create_db.sh` script to create the database and user.**
    - **On a standard setup:**
      ```bash
      ./cs166_project_phase3/sql/scripts/create_db.sh
      ```
    - **If on CS166 PSQL Server:**
      ```bash
      source sql/scripts/create_db.sh
      ```

3. **Update `load_data.sql` with correct file paths.**

4. **Run the `compile.sh` script to compile the Java source files.**
    - **On a standard setup:**
      ```bash
      ./cs166_project_phase3/java/scripts/compile.sh
      ```
    - **If on CS166 PSQL Server:**
      ```bash
      source java/scripts/compile.sh
      ```

5. **Follow the On-Screen Instructions**
    - Interact with the program using the menu options provided.
