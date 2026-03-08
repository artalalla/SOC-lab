# SOC Lab

## Objective

The objective of this project is to build a mini Security Operations Center (SOC) lab using Wazuh SIEM and Windows 11 with Sysmon to simulate a real-world cybersecurity environment. This lab allows the collection, monitoring, and analysis of system and network logs, enabling the detection of suspicious activities such as port scans and brute-force attempts.


### Tools Used

- VirtualBox
- Windows 11 VM
- Wazuh Server
- Sysmon

  
## Steps

**Setting up the virtual environments**
<br>Both of the machines' sole network adapters to be configured to Host-Only to be able to communicate with each other to simulate a network.
![Picture1](https://github.com/artalalla/SOC-lab/blob/main/images/1.png)
![Picture2](https://github.com/artalalla/SOC-lab/blob/main/images/2.png)<br><br>

**Deploying the Wazuh server**
<br>Setting up the server and accessing it with the default credentials.
![Picture3](https://github.com/artalalla/SOC-lab/blob/main/images/3.png)<br><br>

**Setting up the Windows 11 machine as the Wazuh agent**
<br>Installing Sysmon for detailed event logging and the Wazuh Agent on the Windows 11 VM.
![Picture4](https://github.com/artalalla/SOC-lab/blob/main/images/4.png)
![Picture5](https://github.com/artalalla/SOC-lab/blob/main/images/4b.png)<br><br>

**Acessing the Wazuh Dashboard**
<br>Installing Wazuh Agent on the Windows 11 VM.
![Picture6](https://github.com/artalalla/SOC-lab/blob/main/images/5.png) 
![Picture7](https://github.com/artalalla/SOC-lab/blob/main/images/6.png)<br><br>

**Viewing security events**
<br>Viewing activity colected by the Wazuh agent.
![Picture8](https://github.com/artalalla/SOC-lab/blob/main/images/7.png)<br><br>

