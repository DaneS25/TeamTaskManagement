# Daily Standup / Task Management App

This repository is for a **Daily Standup / Task Management App** designed to streamline team meetings and track progress on tasks in a structured, efficient manner. The goal of this app is to help teams manage their daily standup meetings, track task progress, identify blockers, and implement solutions for any barriers to task completion. This app will be built using **Power Platform**, specifically using **Model-Driven Apps**.

## Current Status
As of now, the **Entity Relationship Diagram (ERD)** has been created to outline the key components and structure of the app. The ERD represents the relationships between different entities such as **Teams**, **Tasks**, **Standup Meetings**, **Barriers**, and **Solutions**.

### ERD Overview:
- **Entities** include:
  - **Team**: Represents the team involved in standup meetings.
  - **Standup Meeting**: Represents a daily meeting where each team member provides updates on their tasks.
  - **Team Member**: Represents the individuals in the team.
  - **Task**: Represents the tasks assigned to team members.
  - **Barrier**: Represents any obstacles that hinder task completion.
  - **Solution**: Represents the actions taken to overcome barriers.
  
- **Relationships**:
  - One **Team** can have many **Standup Meetings**.
  - One **Team** can have many **Team Members**.
  - One **Team Member** can have many **Tasks**.
  - One **Standup Meeting** can have many **Tasks**.
  - One **Task** can have many **Barriers**.
  - One **Barrier** can have many **Solutions**.

### Next Steps:
The next phase of this project will involve:
- **Building the Model-Driven App** using **Power Platform**.
  - **Entities and Relationships** defined in the ERD will be implemented in the Power Platform environment.
  - Forms, views, and dashboards will be created to provide users with an intuitive interface for managing tasks, identifying barriers, and tracking solutions.
  - Automation using **Power Automate** will be integrated to provide notifications and updates.

