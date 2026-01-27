<h1>Creating Organizational Units and User Accounts (In progress)</h1>

<h2>Objective</h2>
This SOP describes how to orgainze Active Directory Server into Orgainization Units to orgainize new user accounts in a professional setting

<h2>Utilities Used</h2>

- <b> Microsoft Azure</b>
- <b> Active Directory</b>
- <b> Windows Server 2025</b>

<h2>Key Steps</h2>

**1. Create an Organizational Unit**

- <b> Under tools open Active Directory Users and Computers</b>
- <b> Right click on mydomain.com.  Under new select Organizational Unit
- <b> Create three different orgainizational units for different regions.  North America, Asia, Europe</b>
<div align="left">
  <table>
    <tr>
      <td><img width="400" src="https://github.com/connorpj-tech/Organizational-Units-and-User-Accounts/blob/main/Active%20Directory%20Users%20and%20Computers.png"/></td>
      <td><img width="400" src="https://github.com/connorpj-tech/Organizational-Units-and-User-Accounts/blob/main/Organizational%20Unit.png"/></td>
      <td><img width="400" src="https://github.com/connorpj-tech/Organizational-Units-and-User-Accounts/blob/main/Regions.png"/></td>
    </tr>
       <td align="center"><b>Users and Computers</b></td>
       <td align="center"><b>Organizational Unit</b></td>
       <td align="center"><b>Regions</b></td>
       </tr>
  </table>
</div>


**2. Adding groups to Organizational Units**

- <b> Right click on a regional organization unit.  Create addition orgainizational unit</b>
- <b> Create units for Users, Computers, and Servers</b>
- <b> Do this for all regions</b>
<div align="left">
  <table>
    <tr>
      <td><img width="400" src="https://github.com/connorpj-tech/Organizational-Units-and-User-Accounts/blob/main/Organizational%20units%20for%20regions.png"/></td>
    </tr>
       <td align="center"><b>Organization Units for Regions</b></td>
       </tr>
  </table>
</div>

**3. Grouping Users**

- <b> Right click on Users to create new groups</b>
- <b> Make Global secuirty groups for Accounting, IT, and Warehouse.  Specify region in the name of the group</b>
- <b> Do this for every region</b>
<div align="left">
  <table>
    <tr>
      <td><img width="400" src="https://github.com/connorpj-tech/Organizational-Units-and-User-Accounts/blob/main/Making%20groups.png"/></td>
      <td><img width="400" src="https://github.com/connorpj-tech/Organizational-Units-and-User-Accounts/blob/main/User%20Departments.png"</td>
    </tr>
       <td align="center"><b>Creating a group</b></td>
       <td align="center"><b>Grouping for Departments></td>
       </tr>
  </table>
</div>

**4. Creating Users**

- <b> Right click on a security group.  Select new user</b>
- <b> Fill out information for new user.  For user ID use first letter of first name and last name
- <b> Create a pasword for user.  Check for user to change password upon logging in.  Click finish
- <b> Create as many users as needed</b>
<div align="left">
  <table>
    <tr>
      <td><img width="400" height="600" src="https://github.com/connorpj-tech/Organizational-Units-and-User-Accounts/blob/main/New%20User.png"/></td>
      <td><img width="400" src="https://github.com/connorpj-tech/Organizational-Units-and-User-Accounts/blob/main/User%20Details.png"/></td>
      <td><img width="400" height="600" src="https://github.com/connorpj-tech/Organizational-Units-and-User-Accounts/blob/main/Set%20Password.png"</td>
    </tr>
       <td align="center"><b>Creating a User</b></td>
       <td align="center"><b>User Details</b></td>
       <td align="center"<>b>Set Password</b><td>
       </tr>
  </table>
</div>
