# Raceday-POE

# Project Overview

RaceDay is an event management system for managing events, participants,
categories, enrolments and race results. The project planning covers a
relational database design, a RESTful API endpoint plan and a SQL Server
database script.

The  folder contains the ERD, API endpoint plan, and SQL database script for the RaceDay Event Management System.

# User Roles

## Organiser

The Organiser is responsible for managing RaceDay events and related
information. Organisers can:

Create RaceDay events

Update existing events

Delete events

Create event categories

Update event categories

Delete event categories

View participants enrolled in their events

Record participant results

Update participant results

## Participant

Participants can:

Register for a RaceDay account

Log in

View their own profile

Update their own profile

View available RaceDay events

View event categories

Enrol in an event category

View their own enrolments

Cancel their enrolments

View their own results

# Database Design

The RaceDay database is implemented using Microsoft SQL Server. The
database contains the entities required for users, organisers,
participants, events, categories, event enrolments and results.

The SQL script defines primary keys, foreign keys, required fields,
unique constraints and validation constraints. Sample data is also
included for organisers, participants, events, categories, enrolments
and results.

# Planning Documents

All planning documents are stored in the /docs folder.

The folder contains:

RaceDay_ERD.png - Entity Relationship Diagram for the RaceDay
database.

RaceDay_API_Endpoint_Plan.md - RESTful API endpoint plan covering
authentication, profiles, events, categories, enrolments and
results.

RaceDay_Database.sql - SQL Server database creation and
sample-data script.

The ERD, API endpoint plan and SQL database script are intended to
remain consistent with one another and provide the basis for Part 2
implementation.

# API Endpoint Plan

The planned RESTful API includes endpoints for:

User registration and login

User profiles

RaceDay events

Event categories

Event enrolments

Event results

The API uses role-based access. Public users can register, log in and
view available event information. Participants can manage their own
enrolments and results, while Organisers manage events, categories,
enrolments and results.

# Technologies

C#

ASP.NET Core Web API

Entity Framework Core

Microsoft SQL Server

SQL Server Management Studio (SSMS)

GitHub

GitHub Actions

Swagger

# GitHub and CI/CD

## CI/CD

GitHub Actions is used to automatically validate the RaceDay project repository. 
The workflow checks that the submitted Part 1 PDF is present in the repository.

The workflow is triggered when changes are pushed to the main branch or when a pull request is created.

A successful workflow run confirms that the required project documentation is available.

## CI/CD Screenshot

<img width="1899" height="886" alt="workflow" src="https://github.com/user-attachments/assets/2c4a3872-1a84-43e1-8b84-d8ee8163522a" />


# Project Demonstration Video

The unlisted YouTube walkthrough should demonstrate:

The RaceDay planning documents

The ERD decisions and relationships

The API endpoint choices

The SQL database design

Running the SQL script in SQL Server Management Studio (SSMS)

# YouTube Link

https://youtu.be/kjC4oFZKeo0

# Repository Structure


Raceday-POE/
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── PROG PART 1.pdf
│
└── README.md

# Development Approach

The project follows a planning-first approach. The ERD defines the
database structure, the API endpoint plan defines the functionality
exposed by the RESTful API, and the SQL script implements the planned
database structure in SQL Server.

# References

Microsoft (2024) CREATE TABLE (Transact-SQL). Microsoft Learn.
Available at:
https://learn.microsoft.com/en-us/sql/t-sql/statements/create-table-transact-sql
(Accessed: 3 September 2026).

Microsoft (2024) Primary and foreign key constraints. Microsoft Learn.
Available at:
https://learn.microsoft.com/en-us/sql/relational-databases/tables/primary-and-foreign-key-constraints
(Accessed: 3 September 2026).

Coronel, C. and Morris, S. (2019) Database Systems: Design,
Implementation, & Management. 13th edn. Boston: Cengage Learning.

# Author

Student: Funanani Nelitshindwe

Project: RaceDay Event Management System
