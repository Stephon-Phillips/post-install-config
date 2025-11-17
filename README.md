<img width="960" height="442" alt="admin_settings_comp_logos" src="https://github.com/user-attachments/assets/c605bb76-220e-4726-9c3a-0d0863789e78" />

<h1> osTicket Post-Installation Walkthrough </h1>

This walkthrough covers the essential configuration steps that can be performed after installing osTicket. It's a simple guide for the steps of accessing the system, setting up user roles, configuring departments, creating help topics, and preparing the helpdesk for real use.

- ### [YouTube: Walkthrough steps of OSticket](https://youtu.be/JLm1Y4ybWFw)
---

## Table of Contents
- [Accessing osTicket](#accessing-osticket)
- [System Panels Overview](#system-panels-overview)
- [Configuring Roles](#configuring-roles)
- [Configuring Departments](#configuring-departments)
- [Configuring Teams](#configuring-teams)
- [User Access Settings](#user-access-settings)
- [Adding Agents](#adding-agents)
- [Adding End Users](#adding-end-users)
- [SLA Configuration](#sla-configuration)
- [Creating Help Topics](#creating-help-topics)

---


## Accessing osTicket
<table>
  <tr>
    <td><img width="1920" height="1080" alt="Screenshot (217)" src="https://github.com/user-attachments/assets/9ed0c2ca-a014-4e8b-bfca-1e66466186d4"" /></td>
    <td><img width="1920" height="1080" alt="Screenshot (218)" src="https://github.com/user-attachments/assets/49d88795-111a-416b-819c-381c0ae960dc" /></td>
  </tr>
</table>

**Admin or Analyst Login:**  
`http://localhost/osTicket/scp/login.php`

**End User Portal:**  
`http://localhost/osTicket`

These two URLs provide access to the administrative tools and public ticket submission portal.

---

## System Panels Overview
<table>
  <tr>
    <td><img width="1920" height="1080" alt="Screenshot (217)" src="https://github.com/user-attachments/assets/ded24968-f764-4ce2-994f-d2e01a0bac0f" /></td>
    <td><img width="1920" height="1080" alt="Screenshot (218)" src="https://github.com/user-attachments/assets/d54f9eae-740c-42c8-8991-ea0cce2e24b7" /></td>
  </tr>
</table>
osTicket has two main panels:

- **Agent Panel**: Used for managing and responding to tickets.  
- **Admin Panel**: Used for configuring the helpdesk system, managing users, and defining rules.

Understanding the difference is important when navigating configuration options.

---

## Configuring Roles

Navigate to:  
**Admin Panel → Agents → Roles**

Roles define what permissions an agent has.  
Example:  
- **Supreme Admin** for full access  
- Roles for limited access depending on duties

---

## Configuring Departments

Navigate to:  
**Admin Panel → Agents → Departments**

Departments control ticket visibility and determine workflow boundaries.  
Example Department:  
- SysAdmins  
- Support Team  

---

## Configuring Teams

Navigate to:  
**Admin Panel → Agents → Teams**

Teams allow grouping of agents from different departments for specific purposes.  
Example Team:  
- Online Banking Support

---

## User Access Settings

Navigate to:  
**Admin Panel → Settings → User Settings**

Update access rules:  
- Uncheck: *Unregistered users can create tickets*  
- Check: *Registration Required*  

These settings define how users are allowed to submit tickets.

---

## Adding Agents

Navigate to:  
**Admin Panel → Agents → Add New**

Add internal staff who will work on tickets.  
Example Agents:  
- Jane (Department: SysAdmins)  
- John (Department: Support)

---

## Adding End Users

Navigate to:  
**Agent Panel → Users → Add New**

Add customers or employees who will submit tickets.  
Example Users:  
- Karen  
- Ken

---

## SLA Configuration

Navigate to:  
**Admin Panel → Manage → SLA**

Set response and resolution expectations.  
Example SLAs:  
- **Sev 1**: 1 hour, 24/7  
- **Sev 2**: 4 hours, 24/7  
- **Sev 3**: 8 hours, Business Hours  

---

## Creating Help Topics

Navigate to:  
**Admin Panel → Manage → Help Topics**

Help topics are categories that users select when submitting tickets.  
Example Topics:  
- Business Critical Outage  
- Personal Computer Issues  
- Equipment Request  
- Password Reset  
- Other  

---
