# Brute-Force-Attack-Detection-with-Snort


## Objective

Complete a TryHackMe lab by detecting and mitigating a brute-force attack targeting J&Y Enterprise’s digital assets using Snort. The task involves identifying the attack source, targeted service, and port and implementing an Intrusion Prevention System (IPS) rule to block malicious traffic. Successfully stopping the attack will generate a flag text, marking the lab’s completion.

## Skills Learned

- Network Traffic Analysis
- Intrusion Detection and Prevention
- Writing Snort Rules
- Cybersecurity Incident Response
- Hands-on experience with Snort in Sniffer and IPS modes
  
## Tools Used

- TryHackMe paltform for accessing the Lab
- Snort: Open-source intrusion detection and prevention system
- Ubuntu Terminal: Command-line interface for executing Snort commands
- Virtual Machine (VM): Simulated environment for executing tasks

## Steps Taken

1. Traffic Observation:
   - Started Snort in logging mode to analyze incoming traffic.
  <img src="https://github.com/user-attachments/assets/59e8c8f0-5007-47cd-b8bc-bd3a2be79a20"></img>
   - Identified the attack source, target service (SSH), and port (TCP/22).
   <img src="https://github.com/user-attachments/assets/c0c6fc25-3d13-42c1-8f9a-e32738c77d04"></img><br>
   <img src="https://github.com/user-attachments/assets/f71ca24e-da55-4de0-86e4-a3629e2dd7f5"></img>

2. Creating an IPS Rule:
   - Developed a Snort rule to detect and block brute-force attempts
  <img src="https://github.com/user-attachments/assets/7187c824-1c90-475c-9135-8776bc0c1dc8"></img>

3. Running Snort in IPS Mode:
   - Executed Snort in "-A full" mode with the default log path.
 <img src="https://github.com/user-attachments/assets/69b8fc34-d0d6-40c4-a2d6-3b3d5f389297"></img>
 
4. Confirming Mitigation:
   - Retrieved the flag file from the desktop:<br>
          - THM{81b7fef657f8aaa6e4e200d616738254}


## Conclusion

This project demonstrated the importance of real-time intrusion detection and prevention in cybersecurity. By using Snort, we effectively identified and mitigated a brute-force attack targeting SSH on TCP port 22. The hands-on experience reinforced key SOC analyst skills, including traffic analysis, rule creation, and incident response.
