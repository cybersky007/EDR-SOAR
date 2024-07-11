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
 
Installing the Wazuh instance through Linode Cloud provider: 
 
 <br/>
 <img src="https://imgur.com/ez28QqM.png" height="80%" width="80%" "/>
<br />
<br />
 Deploying a new Wazuh agent from the portal:
<img src="https://imgur.com/C1hX2Xy.png" height="80%" width="80%" />
<br />
<br />
Installing the wazuh configuration with Windows powershell on Windows 11 agent: <br/>
<img src="https://imgur.com/9Hy24zZ.png" height="80%" width="80%" />
<br />
<br />
Staring the Wazuh service on the agent:  <br/>
<img src="https://imgur.com/qzwMFS4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />Two agents deployed as wazuh agents :- Windows Machine and Kali Linux :  <br/>
<img src="https://imgur.com/rzU7LVR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Security configuration assessment of agent  <br/>
<img src="https://imgur.com/EbqGCS2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Security Configuration assessment  <br/>
<img src="https://imgur.com/LcnBwQ9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Editing the OSSEC.confg file for active response on rule based Wazuh detection and i also changed the time from 180 to 30 just to block a user after an invalid authentication  <br/>
<img src="https://imgur.com/lTb66Ck.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Editing the configuration file to alter the Vulnerability assessment check to YES  <br/>
<img src="https://imgur.com/kU6lpM8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
