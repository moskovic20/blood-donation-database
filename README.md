# Blood Donation Database

## Overview
This project is a database system for managing blood donations for Magen David Adom (MDA).

The system is designed to store, manage, and analyze data related to donors, donation stations, and blood bank orders.

It supports locating suitable donors based on blood type requirements, retrieving detailed data for research, and managing blood unit orders for hospitals.

## Features

- Track donor information  
- Manage donation stations  
- Process blood bank orders  
- Locate suitable donors based on blood type  
- Retrieve data for analysis and research  

## Database Design

The database was designed using:
- ERD (Entity-Relationship Diagram)  
- DSD (Data Structure Diagram)  

The schema includes relationships between entities such as:
- `belong_To` – associates a donor with a blood type  
- `tookPlaceIn` – records where a donation occurred  

Data normalization was applied up to BCNF and 3NF to ensure data integrity.

## Technologies

- PL/SQL  
- Oracle Database  

## ERD Diagram

![ERD Diagram](https://github.com/moskovic20/DBProject_6941_9320/blob/main/DBProject_6941_9320/%D7%AA%D7%9E%D7%95%D7%A0%D7%95%D7%AA/ERD.png)

## Additional Information

For full project documentation:  
[View full project report](https://github.com/moskovic20/DBProject_6941_9320/blob/main/DBProject_6941_9320/%D7%A9%D7%9C%D7%91%20%D7%93/%D7%93%D7%95%D7%97%20%D7%94%D7%A4%D7%A8%D7%95%D7%99%D7%A7%D7%98%20%D7%A9%D7%9C%D7%91%20%D7%93.pdf)

## Notes

This project was developed as part of academic studies.
