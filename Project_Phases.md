PHASE 1 – BRAINSTORMING & IDEATION

Project Title:
Script-Controlled ACL – Restrict Record Access Based on Field Value

Project Idea:
To implement a script-controlled Access Control List (ACL) in ServiceNow to restrict users from viewing records based on the Branch field and user roles.

Problem Statement:
Unauthorized users should not be allowed to access restricted records. The project provides record-level security using ServiceNow ACLs.
PHASE 2 – REQUIREMENT ANALYSIS

Software Requirement:
1. ServiceNow Instance
2. Admin Access
3. User Management
4. Access Control List (ACL)

User Requirement:
1. EEE User
2. Roles: bb1, bb2, bb3, bb4

Table Requirement:
Table Name: Institution Details
Table Name: u_institution_details

Fields:
1. Student Roll Number
2. Student Name
3. Faculty Name
4. Branch
5. Email
6. Phone Number
7. Description

Branch Values:
ECE, EEE, CSE
PHASE 3 – PROJECT DESIGN

The project is designed using ServiceNow ACLs.

Role and Permission Design:

bb1 – Read Access
bb2 – Create Access
bb3 – Write Access
bb4 – Delete Access

The Read ACL uses the Branch field condition.

Only users with the required role can access the allowed records, while administrators have full access.
PHASE 4 – PROJECT PLANNING

Project Development Steps:

1. Create the EEE User.
2. Create roles bb1, bb2, bb3 and bb4.
3. Assign roles to the user.
4. Create the Institution Details table.
5. Create the required fields.
6. Create records with ECE, EEE and CSE branch values.
7. Create Read ACL.
8. Create Create ACL.
9. Create Write ACL.
10. Create Delete ACL.
11. Test and verify the ACL permissions.
PHASE 5 – PROJECT DEVELOPMENT

The project was implemented in ServiceNow.

1. Created EEE User.
2. Created roles bb1, bb2, bb3 and bb4.
3. Created Institution Details table.
4. Added required fields.
5. Created records with different branch values.
6. Created Read ACL with Branch = EEE condition.
7. Created Create ACL using bb2 role.
8. Created Write ACL using bb3 role.
9. Created Delete ACL using bb4 role.
PHASE 6 – PROJECT TESTING

Testing was performed by impersonating different users.

Test Results:

1. User with bb1 role can view EEE branch records.
2. User without the required role cannot view the records.
3. Admin user can view all records.
4. User with bb2 role can create records.
5. User with bb3 role can edit records.
6. User with bb4 role can delete records.

The ACL permissions were verified successfully.
PHASE 7 – PROJECT DOCUMENTATION

Project Title:
Script-Controlled ACL – Restrict Record Access Based on Field Value

Objective:
To provide record-level security in ServiceNow using script-controlled ACLs.

The project demonstrates READ, CREATE, WRITE and DELETE access control using user roles and record field values.

Tools Used:
ServiceNow

Main Components:
1. Users
2. Roles
3. Institution Details Table
4. Records
5. Access Control Lists
6. ACL Script

Conclusion:
The project demonstrates how ServiceNow ACLs can be used to control access to records and protect data from unauthorized access.
PHASE 8 – PROJECT DEMONSTRATION

The project demonstration video includes:

1. Project Name
2. Purpose of the Project
3. Uses and Benefits
4. Project Execution and Working Process
5. Demonstration of ACL permissions
6. Final Output

The complete project demonstration is recorded with screen sharing and voice-over explanation.

The demo video is uploaded to Google Drive and the public/viewer link is provided for submission.
