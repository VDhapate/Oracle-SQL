<-------College Event Participation System🏫🎓------->
A Relational Database project designed to manage college fest activities. This project is implemented using Oracle SQL RDBMS

<-------📽️Project Overview🏫🎓------->
This System tracks which student paarticipated in which events, who is organizing them, and where they are held. 
It enforces data integrity through foreign key, primary key and specific relationships.

<-------🏗️ Database Schema------->
1.TABLE_NAME  = Department 
            COLUMNS = department_ID as deptid (PK), department_name as deptnm.
2.TABLE_NAME  = organizer 
            COLUMNS = Organizer_ID as orgid (PK), organizer_name as orgname, role as role.
3.TABLE_NAME  = venue 
            COLUMNS = Organizer_ID as vid (PK), venue_name as vname, capacity as capacity.
4.TABLE_NAME  = student as stud
            COLUMNS = student_ID as sid (PK), student_name as sname, gender as gender, mobile_no as mno, department_id as deptid.
