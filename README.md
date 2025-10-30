# SOC Automation Project 

## Objective

The objective of the (SOC) automation project is to show how to integrate a suite of open-source tools: Wazuh will serve as the primary host-based security monitoring and endpoint detection and response (EDR) platform, providing real-time alerts and security event data. This data will be ingested by The Hive, which will function as the central, collaborative Security Incident Response Platform. Then Shuffle will be used as an orchestrator that will automate security tasks, or 'playbooks,' triggered by alerts from Wazuh via The Hive. A key deliverable of this automation is the capability to create and send automated emails for high-severity alerts, ensuring immediate, reliable notification of relevant stakeholders without manual intervention, thereby reducing the mean time to detect (MTTD) and mean time to respond (MTTR) to security incidents.

### Skills Learned 

- Installation and coniguration of servers using the cloud.
- Index creation and generating telemetry using Wazuh.
- Using the command line to configure Wazuh, Elasticsearch, and The Hive.
- Configuration of conf files in Windows.
- Creating custom rules for Wazuh.
- Using Shuffler.io for workflow automation and orchestration.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Sysmon 
- Vultr to create two servers (Wazuh and The Hive).
- Wazuh as a SIEM and EDR Tool.
- The Hive as an Incident Platform.
- Powershell to configure Wazuh, Elasticsearch, and The Hive.
- Telemetry generation tools to create realistic endpoint detection.
- Shuffler.io for workflow automation and configure email notification.

## Steps

*Ref 1: Installation of Sysmon*

<img width="1920" height="1080" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/cd9a5b16-a077-4d71-9526-71b3402178ed" />

*Ref 2: Using Vultr to create a Wazuh server and a server for The Hive*

<img width="1920" height="1080" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/c0b96d46-0aab-42fb-b5e3-7c0182a83b20" />

*Ref 3: Index creation and generarting Telemetry using Wazuh*

<img width="1530" height="750" alt="Screenshot (68)" src="https://github.com/user-attachments/assets/803224db-6740-40be-a80a-2cbddb47ecd3" />

<img width="1530" height="750" alt="Screenshot (68)" src="https://github.com/user-attachments/assets/a8d1ef5b-925b-4083-ba96-302c1e1d9478" />

*Ref 4: Mimikatz execution to create telemetry in Wazuh*

<img width="1530" height="750" alt="Screenshot (70)" src="https://github.com/user-attachments/assets/7c3f167b-5b47-43aa-ac93-2f57a17856a3" />

*Ref 5: Configuration of Wazuh*

<img width="1530" height="750" alt="Screenshot (67)" src="https://github.com/user-attachments/assets/16f918ad-df7a-4855-b059-6fd6203354e9" />

*Ref 6: The Hive*

<img width="1530" height="750" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/1160dbab-0d73-4e7d-8ce0-d616d81ab2b5" />

*Ref 7: Shuffler.io for worflow automation and orchestration*

<img width="1530" height="750" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/a1eb2031-90ed-469d-a777-cb212a0ed0e1" />

*Ref 8: email notification using Shuffle*

<img width="1530" height="750" alt="Screenshot (83)" src="https://github.com/user-attachments/assets/58fb5621-ecd5-4314-a00d-b092bdbf5433" />









