# dataexpandvis_sql
SQL Data Exploration and Visualization

## Lesson 1 — Basic SQL with the World Cup Database

This folder contains the material for **Lesson 1** of the SQL course.
The lesson introduces the core ideas of relational databases and basic SQL through a structured, real dataset: the **World Cup football database**.

### Folder contents

#### `basic_sql.pdf`

Main introductory presentation or background material.

#### `SQL_Basic_2026_1.ipynb`

Main introductory notebook for the lesson.

This notebook focuses on:

* the role of SQL in data analysis
* connecting Python to SQLite
* exploring the database structure
* inspecting tables and schemas
* writing progressively more meaningful SQL queries
* connecting query results to simple analytical questions and visualizations

#### `SQL_Basic_2026_2_bracket.ipynb`

A follow-up notebook that demonstrates a more advanced example.

Here, SQL query results are used to reconstruct and visualize the **2022 World Cup knockout bracket**, including the third-place match.
This notebook shows how relational data can be transformed into a structural representation and then into a clear custom visualization.

#### `worldcup.db`

A local SQLite database containing the World Cup data used throughout the lesson.

This is the core data source for both notebooks.

#### `vb_schema_all.png`, `brackets_schema.png`

Schema illustrations that help students understand the structure of the database and the relationships between tables.

#### Data source

The lesson uses the World Cup Database created by Jake Fjelstul (https://github.com/jfjelstul/worldcup).
This public dataset is available on GitHub and contains structured information about FIFA World Cup tournaments, matches, teams, players, goals, lineups, and tournament stages.
