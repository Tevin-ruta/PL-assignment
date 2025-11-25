# PL-assignment
RUTAYISIRE Tevin 27343
Hospital Inventory Management – PL/SQL Project


Overview

This project demonstrates the use of PL/SQL Collections, Records, and GOTO statements through a practical scenario of managing a hospital’s medicine inventory. The goal is to show how composite data types in PL/SQL can be used to model real-world systems efficiently.

Project Objectives

This project covers the following PL/SQL concepts:

✔ PL/SQL Collections (Nested Table)

Used to store a list of medicines with dynamic sizing.

✔ PL/SQL Records

Used to define a custom structure representing each medicine:

Medicine ID

Medicine Name

Quantity

Reorder Level

✔ GOTO Statements

Used to skip processing medicines with zero stock.

Problem Description

A hospital pharmacy stores and manages medicine details. Each medicine has:

Medicine ID

Medicine Name

Quantity in Stock

Reorder Level

Your PL/SQL program must:

Store multiple medicines using a collection of records

Skip medicines that have quantity = 0 using GOTO

Identify medicines below their reorder level

Print all medicines requiring restocking

This simulation is implemented using Oracle PL/SQL.

Technology & Features Demonstrated
Feature	Description
Record Types (User-defined)	For storing heterogeneous data fields together
Collections (Nested Table)	For storing multiple record entries
GOTO / Labels	For skipping elements under certain conditions
DBMS_OUTPUT	For displaying results


