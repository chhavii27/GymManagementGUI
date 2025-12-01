# FitZone - Health and Fitness Club Management System

FitZone is a desktop application for managing a health and fitness club. It provides separate dashboards for Members, Trainers, and Administrators to manage memberships, classes, personal training sessions, health metrics, and billing.

# Overview
# Member Features

Registration & Login – Secure account creation and authentication
Member Dashboard – Quick access to recent metrics, active goals, booked classes, and upcoming PT sessions
Health Metric Tracking – Record weight, heart rate, blood pressure, body fat %, and steps (system automatically applies units such as kg, bpm, mmHg, etc.)
Goal Setting – Define and monitor personal fitness goals
Book PT Sessions – View trainer availability in real-time; double-click a slot to auto-fill booking details
Join Group Classes – Browse and register for club classes
Manage Profile – Update personal details anytime
Billing History – View all past invoices and payments

# Trainer Features
Set Availability – Add or update available time slots
Member Lookup – View details of members you train
Schedule Overview – Track upcoming sessions and classes
Trainer Dashboard – Snapshot of your current workload and availability

# Admin Features
Room Scheduling & Management
Class Creation & Management – Define class schedules, capacities, and instructors
Billing System – Handle payments and generate bills
User Management – Manage all members and trainers
Admin Dashboard – High-level view of club activity and operations

# Technical Prerequisites
Java version 25.0.1
Make a postgreSQL database named "health_club_management" or update your credentials in hibernate.cfg.xml
Maven, JDBC, FlatLaf and Jcalendar has dependencies added to pom.xml 

# Installation
i) git clone https://github.com/priitttt/health_club_management.git
cd health_club_management

ii) Open pgAdmin4 create a new database name health_club_management

iii) open hibernate.cfg.xml and update to your credentials

iv) Build the project using "mvn clean install"

v) Open Intellij IDE, run main.java

# Troubleshooting

i) Check if you're running main.java and no other file is selected

ii) Check if database name and credentials matches to those in hibernate.cfg.xml

iii) Verify if you have java installed in it, and it is not a local device issue

# Link to Demo Video
