**Gaming-Database-System**
**SQL Based Gaming Database System**

**Project Description**
The Gaming Database System is a SQL-based project designed to manage player accounts, characters, items, and game interactions. It demonstrates database concepts such as entity relationships, queries, stored procedures, and triggers.

**🎯 Objectives**
Manage player accounts
Store character information
Manage game items
Track character-item relationships
🛠️ Technologies Used
MySQL Database
ER Diagram Design


**📂 Database Tables**
**Main tables used in this project:**

Account
Character
Item
Creep
Region
Item Instantiation
Creep Instantiation


**Relationship tables used in this project:**

Has - Account & Character
Contains - Region & Character
Carrying - Character & Item Instantiation
Contains - Region & Creep Instantiation
RanInto - Character & Creep
Carrying - Item Instantiation & Creep Instantiation
IsType - Item & Item Instantiation
IsType - Creep & Creep Instantiation


**Features**
Player account management
Character creation
Item management
Database queries for game statistics
Stored procedures
Database triggers


**Gaming-Database-System Structure** │ ├── Database │ ├── create_tables.sql │ ├── insert_data.sql │ ├── queries.sql │ ├── procedures.sql │ └── triggers.sql │ ├── ER_Diagram │ └── gaming_er_diagram.png │ └── README.md
