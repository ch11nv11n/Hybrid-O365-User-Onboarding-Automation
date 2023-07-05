# Hybrid-O365-User-Onboarding-Automation
<p>This repository hosts a collection of PowerShell scripts designed to streamline the process of onboarding a new user in a hybrid Microsoft Office 365 environment. The scripts cover Active Directory User Creation, Exchange Online Mailbox Provisioning, and Office 365 License Assignment, thereby making the user onboarding process efficient and error-free.</p>
<h3>Scripts in this Repository:</h3>
<ol>
  <li><b>Active Directory User Creation:</b> This script creates a new user in the local Active Directory. It collects necessary user details like First Name, Last Name, User Principal Name, Password, and other important information. It also handles user group assignment based on the department.</li>
  <li><b>Exchange Online Mailbox Provisioning:</b> This script establishes a connection with Exchange Management Shell on a hybrid server and creates a mailbox for the newly created user. It enables a remote mailbox and routes the user's emails to the Office 365 cloud-based service.</li>
  <li><b>Office 365 License Assignment:</b> This script assigns Office 365 licenses to the new user. The user can choose from various license types (E3, F1, Power BI Standard, Visio, Project Online Pro), and the script handles all the back-end operations necessary for license assignment.</li>
</ol>
<h3>Getting Started</h3>
<p>Clone this repository to your local machine where you have administrative privileges:</p>
<code>git clone https://github.com/username/HybridO365UserOnboardingAutomation</code>
<h4>Prerequisites</h4>
<ol>
  <li>PowerShell v5.1 or later</li>
  <li>Administrative access to Active Directory</li>
  <li>MSOnline PowerShell module</li>
  <li>Administrative access to Office 365 and Exchange Online</li>
  <li>Appropriate permissions to assign licenses in Office 365</li>
</ol>
<h4>Usage</h4>
<p>
  Before running these scripts, make sure to modify them according to your environment, e.g., domain name, server URI, etc.
  <br><br>
  Then, run the scripts in the following order:
  <ol>
  <li>Pt1-ADUserCreation.ps1</li>
  <li>Pt2-ExchangeMailboxCreation.ps1</li>
  <li>Pt3-OfficeLicenseAssignment.ps1</li>
</ol>
Each script will ask for the necessary input at runtime.
</p>
<h4>Disclaimer</h4>
<p>Use these scripts at your own risk. Always test any script in a development environment first before running it in production.</p>
<h4>Contributing</h4>
<p>Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.</p>
<h4>Authors</h4>
    <p>ch11nv11n
    <br>
    Your Contact Information
    <ul><li><b>DISCORD</b>: ch11nv11n</li></ul>
    </p>
<h4>License</h4>
<p>This project is licensed under the MIT License - see the LICENSE file for details.</p>
