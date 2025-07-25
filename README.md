# Active Directory Group Policy Management Lab
<p align="center">
<img width="566" src="https://www.31west.net/wp-content/uploads/2022/11/what-is-active-directory-and-why-is-it-used.png.avif" alt="active directory logo" /> </p>

<h1>Part I: Navigating Group Policy Object (GPO) in On-Premises Active Directory</h1>
<p>I will be demonstrating and explaining the processes of creating, setting up, applying, and testing GPOs in this Group Policy Management lab that is easily implementable through a virtualized Windows Server environment.</p>

<p>GPOs are an important aspect of Active Directory and provide centralized management over various settings and configurations on users' and computers' environments. In terms of what they are, GPOs typically refer to a multitude of settings defining what a user or computer is allowed to do on a network. They are administrative tools best for enforcing consistency, stability, and secure network environments.</p>

<p>The cool thing about this lab is you can practice multiple key IT skills at once. Active Directory is such a broad tool that this one lab geared towards Group Policy Management will have you dabbling in cybersecurity policy, desktop configuration and software deployment, remote IT administration, and more!</p>

<h2>What's on the Agenda</h2>

  1. Setting a password policy
  2. Mapping network drives for users
  3. Restricting user access to the control panel
  4. Account lockout policy
  5. Creating and setting up a Windows Client VM
  6. Applying & testing GPOs

**Setting a Password Policy**

<p>Before I get into password policy work, I have to go over how to get to your Group Policy Management or GPM console. Unlike when we were working with Active Directory Users and Computers, GPM will not be in the startup menu. It is actually a separate app that should already be pre-installed on your Windows Server VM. Simply search for it on your VM and it should be the first choice that pops up. Click and open it up. Navigate to your domain, then Group Policy Objects, then right click Default Domain Controllers Policy. </p>

<img src="screenshot_1.png">
