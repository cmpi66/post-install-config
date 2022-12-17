<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Install Configuration
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.


## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used 

- Windows 10 (21H2)

## Post-Install Configuration Objectives

- Configuring roles
- Defining SLAs 2
- Allow anyone to create tickets
- Creating teams
- Creating departments

Now that we have osTicket installed let's configure it for our organization.

## Configure Roles

Admin Panel -> Agents -> Roles then add a new role and assign the proper permissions

- Supreme Admin

![adding roles](./add-role.png)

## Configure Departments

Admin Panel -> Agents -> Departments

- System Administrators

![adding deps](./adding-departments.png)

## Configure Teams

Admin Panel -> Agents -> Teams

- Level I Support
- Level II Support

![adding deps](./teams.png)

## Allow anyone to create tickets

- Admin Panel -> Settings -> User Settings
- Registration Required: Require registration and login to create tickets 

## Configure Agents (workers)

Admin Panel -> Agents -> Add New

- Jane
- John

![adding agents](./adding-agents.png)

## Configure Users (customers)

Agent Panel -> Users -> Add New

- Karen
- Ken

![adding users](./users.png)

## Configure SLA

Admin Panel -> Manage -> SLA

- Sev-A (1 hour, 24/7)
- Sev-B (4 hours, 24/7)
- Sev-C (8 hours, business hours)

![adding SLAs](./slas.png)

## Configure Help Topics

Admin Panel -> Manage -> Help Topics

- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset


![adding help topics](./help-topics.png)
