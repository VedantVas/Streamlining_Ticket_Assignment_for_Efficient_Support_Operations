# Streamlining_Ticket_Assignment_for_Efficient_Support_Operations
Metro Ticket Generating System (ServiceNow Automation)
📌 Project Overview

The Metro Ticket Generating System is an automated ticket routing system built using ServiceNow. The project aims to streamline the process of assigning support tickets to the appropriate teams based on the issue type.

Instead of manually routing tickets, the system automatically assigns them to the correct support group, improving operational efficiency and reducing resolution time.

🎯 Objective

The main objective of this project is to:

Automate the ticket assignment process

Reduce manual intervention in ticket routing

Improve customer issue resolution time

Increase support team efficiency

⚙️ Technologies Used

ServiceNow Platform

Flow Designer

Access Control Lists (ACL)

Role-Based Access Control

Custom Tables

🧩 Project Components
1️⃣ Users

Users are created in ServiceNow who will manage or handle tickets.

2️⃣ Groups

Two main groups are created:

Certificates Group

Platform Group

These groups handle tickets related to their respective domains.

3️⃣ Roles

Roles define access permissions for users:

Certification_role

Platform_role

4️⃣ Custom Table

A table named Operations Related is created to store ticket details such as:

Assigned group

Assigned user

Issue

Priority

Service request number

Ticket raised date

5️⃣ Access Control (ACL)

ACL rules are implemented to ensure secure access to the table and restrict unauthorized users.

🔄 Workflow Automation

Two automated flows are created using ServiceNow Flow Designer.

Flow 1: Certificate Issues

If the issue is related to Certificates, the ticket is automatically assigned to the Certificates Group.

Flow 2: Platform Issues

If the issue includes:

Unable to login to platform

404 Error

User expired

The ticket is automatically assigned to the Platform Group.

🚀 How It Works

A ticket is created in the Operations Related table.

The system checks the issue type.

Based on the issue condition, the Flow Designer automatically assigns the ticket to the correct group.

The support team resolves the issue.

📊 Benefits

Faster ticket routing

Reduced manual work

Improved operational efficiency

Better issue resolution time

Organized support workflow

📄 Conclusion

This project demonstrates how ServiceNow automation can improve support ticket management by implementing automated workflows and role-based access control, ensuring tickets are quickly routed to the correct teams for resolution.
