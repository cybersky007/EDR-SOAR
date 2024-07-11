<h1>EDR-SOAR Homelab</h1>



<h2>Description</h2>
In this project, I implemented a detection mechanism in Lima Charlie to identify the presence of a specific hack tool. Upon detection, the system triggers actions via Tines, sending notifications to Slack and email. These notifications include crucial details such as timestamp, computer name, source IP, process details, command line invocation, file paths, sensor ID, and optionally, a link to detailed detection information. Furthermore, Tines prompts the user with an option to isolate the affected machine. If isolation is confirmed, Lima Charlie automates the isolation process and notifies Slack with a confirmation message indicating the action. If isolation is declined, a message is sent confirming the decision, advising further investigation
<br />


<h2>Environments/Tools Used</h2>

- <b>LimaCharlie - EDR</b> 
- <b>Tines </b>
- <b>Slack</b>

<h2>Program walk-through:</h2>

<p align="center">
<br />
 
SOAR-EDR Playbook Workflow guide/diagram of the project/lab: 
 
 <br/>
 <img src="https://imgur.com/cNXT7Wr.png" height="80%" width="80%" "/>
<br />
<br />
 Creating an installation key as the first step in the LimaCharlie interface :
<img src="https://imgur.com/0R6cvl2.png" height="80%" width="80%" />
<br />
<br />
Installing the LimaCharlie executable with Windows powershell on Windows 11 agent: <br/>
<img src="https://imgur.com/Icd9fEN.png" height="80%" width="80%" />
<br />
<br />
LimaCharlie Service running on the agent/system/Window 11 machine:  <br/>
<img src="https://imgur.com/ZW8IjFC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />LimaCharlie is extensively helpful in illustrating the key aspects related to the deployed agent, On the left hand side 
it depicts all information about Autoruns, Console, Drivers, FileSystem etc:  <br/>
<img src="https://imgur.com/QWBMEsr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Even the process management can be handeled from the interface,  <br/>
<img src="https://imgur.com/wE2eCoS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Security Configuration assessment  <br/>
<img src=".png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 authentication  <br/>
<img src=".png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  YES  <br/>
<img src=".png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


                                 
                                 END OF THE PROJECT.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
