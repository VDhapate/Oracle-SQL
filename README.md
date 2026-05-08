<-------College Event Participation System🏫🎓------->
A Relational Database project designed to manage college fest activities. This project is implemented using Oracle SQL RDBMS

<-------📽️Project Overview🏫🎓------->
This System tracks which students participated in which events, who is organising them, and where they are held. 
It enforces data integrity through foreign key, primary key and specific relationships.

<-------🏗️ Database Schema------->
1.TABLE_NAME  = Department 
            COLUMNS = department_ID as deptid (PK), department_name as deptnm.
2.TABLE_NAME  = organizer 
            COLUMNS = Organizer_ID as orgid (PK), organizer_name as orgname, role as role.
3.TABLE_NAME  = venue 
            COLUMNS = venue_ID as vid (PK), venue_name as vname, capacity as capacity.
4.TABLE_NAME  = student as stud
            COLUMNS = student_ID as sid (PK), student_name as sname, gender as gender, mobile_no as mno, department_id as deptid.
5.TABLE_NAME  = event
            COLUMNS = event_ID as eid (PK), event_name as ename, Organization_id as orgid(Fk), venue_ID as vid (FK).
6.TABLE_NAME  = participation as PARTICIPATE
            COLUMNS = participation_ID as partid (PK),student_ID as sid (fK), event_ID as eid (FK), position as position

