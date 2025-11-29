FitZone - Health and Fitness Club Management System

FitZone is a health club management system that lets members set fitness goals, track their progress, and book group classes or private training sessions. Trainers can manage their class schedules and availability, while admins oversee members, trainers, and overall club operations in one place.


FitZone provides following functions for members,
i) User Registration
ii) Group Class Registration
iii) Profile Management
iv) Dashboard
v) Health History
vi) PT Session scheduling For Trainer
vii) View their Bills

For Trainers,
i) Set Availability
ii) Member Lookup
iii) Schedule view for Admin

For admin,
i) Room Booking
ii) Class Management
iii) Billing & Payments 

Technical Requirements,
Note: Please make sure user will have to create a local database in PGadmin4 as we have not connected system to remote database. Just keep the database name as health_club_management and it should be fine.
i) Java version 25.0.1
Dependencies added,
ii) Maven version 3.11.0
iii) Postgresql version 42.7.8
iv) flatlaf version 3.3
v) jcalendar version 1.4
vi) hibarnate-core version 7.1.10.Final

Setup
Clone repository from github (https://github.com/priitttt/health_club_management.git)
Create database named "health_club_management" on your local device
Update DataBase credentials in hibernate.cfg.xml file if needed
run from intelliJ from main class

Project Structure,

health_club_management/src/main/java/main.java -- main class that'll run the application
health_club_management/src/main/java/healthClubManagement/db -- database files(Entities and Operation files)
health_club_management/src/main/java/healthCLubManagement/gui -- UI files for each page

YouTube link to demo video,
--yet to come-- 