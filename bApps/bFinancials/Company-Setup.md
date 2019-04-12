---
title: Install
layout: custom
keywords: [Report, Epicor, Accounts]
description: Step by step guide on data tier, initial data load, FRx Migration, and other key processes of installing of Interject for Financials Epicor.
---

As a prerequisite to installing Interject Financials - Epicor, you will need to submit an invite request form on Interject's [Portal site](https://portal.gointerject.com). You will be asked to fill out the following information:

<table>
  <tr>
    <th>Field</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Company Name</td>
    <td>Client Company Legal Name</td>
  </tr>
  <tr>
    <td>First Name</td>
    <td>Name of Desired Interject admin/ Contact</td>
  </tr>
  <tr>
    <td>Last Name</td>
    <td>Name of Desired Interject admin/ Contact</td>
  </tr>
  <tr>
    <td>Email Address</td>
    <td>Email address of Admin contact</td>
  </tr>
  <tr>
    <td>Phone Number</td>
    <td>Phone # of Admin Contact</td>
  </tr>
  <tr>
    <td>Address</td>
    <td>Client Address</td>
  </tr>
  <tr>
    <td>City</td>
    <td>Client City</td>
  </tr>
  <tr>
    <td>State</td>
    <td>Client State</td>
  </tr>
  <tr>
    <td>Zip</td>
    <td>Client Zip</td>
  </tr>
  <tr>
    <td>Country</td>
    <td>Client Address</td>
  </tr>
  <tr>
    <td>Industry</td>
    <td>Client Industry</td>
  </tr>
  <tr>
    <td># of Employees</td>
    <td>&lt;50, 50-500, &gt; 500</td>
  </tr>
  <tr>
    <td>Yearly Revenue</td>
    <td>Small Cap, Mid Cap, Large cap</td>
  </tr>
  <tr>
    <td>Company Description</td>
    <td>Simple Description of Company</td>
  </tr>
  <tr>
    <td>Planned Use of Interject</td>
    <td>Interject for Financials</td>
  </tr>
</table>

After filling out and submitting the form, you will need to complete the following steps before the actual installation:

> To Do
>
> **Step 1:** Verify SQL Server in Client is Compatible Version
> SQL Server 2008 or greater is required.  
(run "SELECT @@VERSION" in a query window to check version)
>
> **Step 2:** Prepare for using Windows Authentication by creating the active directory user group “Interject Users” on Default SQL Server Domain
>
> ![Active User](/images/A-SQL-Installation/ActiveUser.png){: .center-image }
>
> **NOTE:** If you do not have it, download [SQL Management Studion here](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-2017)
>
>

Within a week you will receive verification from Interject that your company set up and subscription is complete.