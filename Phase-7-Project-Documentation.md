# Phase 7 – Project Documentation

## Project Title

Script-Controlled ACL – Restrict Record Access Based on Field Value

## Objective

The objective of this project is to implement script-controlled ACLs in ServiceNow to control access to records based on user roles and the Branch field.

## Platform Used

ServiceNow

## Table Used

Institution Details

Table Name:
u_institution_details

## ACL Operations

The project implements ACLs for the following operations:

- Read
- Create
- Write
- Delete

## Access Control

The Read ACL restricts record access based on the Branch value. The required role can view the EEE records, while the Admin has full access.

The Create, Write and Delete operations are controlled using the respective roles bb2, bb3 and bb4.

## Testing Result

The ACL functionality was tested with different user roles. The required access was provided according to the assigned roles.

## Conclusion

The project demonstrates how ServiceNow ACLs can be used to provide record-level security and control user access to records based on roles and field values.
