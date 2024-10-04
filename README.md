
<h5>Directory</h5> 

<b>[Tech Portfolio Home](https://github.com/Jays1115/Jalen-Smith.git)</b> /
<b>[AWS Projects  & Labs](https://github.com/Jays1115/AWS-Projects.git)</b>

# AWS Identity Access Management (IAM)

<h2>Description</h2>
Scenario: The city stock exchange is setting up a new Support Engineering team and needs to manage uniform, read-only access to Amazon EC2 and RDS, alongside ensuring secure access to the AWS Management Console and development tools for team members.
<br/> <br/>
Solution: Solution: To streamline permission management for the city stock exchange's new Support Engineering team, I created an IAM group specifically for support engineers and attached a managed EC2 read-only access policy to this group. Then, create IAM users for the team members and assign them to this group to ensure they all have uniform access rights to Amazon EC2, as well as access to the AWS Management Console and necessary development tools.

<h2>Program walk-through:</h2>

<p align="center">
Navigate to IAM dashboard: <br/>
<img src="images/Screenshot 2024-09-27 at 11.03.12 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-27 at 11.03.27 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<p align="center">
Navigated to the User Groups page and created the "SupportEngineers" user group, granting Read-Only access to EC2 instances: <br/>
<img src="images/Screenshot 2024-09-27 at 11.05.26 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-27 at 11.05.57 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-27 at 11.07.03 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-27 at 11.07.35 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<p align="center">
Returned to the recently created "Support Engineers" user group to add Read-Only access to Amazon RDS: <br/>
<img src="images/Screenshot 2024-09-27 at 11.25.19 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-27 at 11.25.51 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="images/Screenshot 2024-09-27 at 11.26.01 AM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

