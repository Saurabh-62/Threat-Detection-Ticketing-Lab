# Threat Detection Ticketing Lab

## Objective
The objective of the Threat Detection Ticketing Lab was to build a security monitoring environment in the cloud, allow public access, create custom attacks, and respond to the attacks through a ticketing system. This experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned
- Using the ELK stack
- Simulating attacks using command and control frameworks
- Creating a ticketing system and responding to tickets

### Tools Used
- Vultr as the cloud platform to deploy Windows and Linux virtual machines
- ELK stack to ingest, monitor, and visualize attacks
- Mythic C2 to create custom attacks
- osTicket as the ticketing system

## Steps
1. Setup the Elastic Stack on a Virtual Machine
<img width="1917" height="1077" alt="Screenshot 2026-03-01 184105" src="https://github.com/user-attachments/assets/d813e078-bf09-4ab3-a4e9-a9ce4a11703a" />
Ref 1: Elastic Homepage
<br> </br>
2. Create a Fleet Server and Agent 
<img width="1387" height="694" alt="Screenshot 2026-03-22 131032" src="https://github.com/user-attachments/assets/d79b042d-c957-4a64-bb66-5a5cbf885227" />
Ref 2: Elastic Agents
<br> </br>
3. Attack the Windows Machine with Mythic
<img width="1919" height="1041" alt="Screenshot 2026-03-03 161633" src="https://github.com/user-attachments/assets/aad451eb-938d-4367-98d6-f3caef0fe9c0" />
Ref 3: Mythic Attack
<br> </br>
4. Create Queries
<img width="1919" height="1021" alt="Screenshot 2026-03-03 143313" src="https://github.com/user-attachments/assets/ff628f28-8f12-4067-9e56-4764454978de" />
Ref 4: SSH Attack Query
<br> </br>
5. Create Visualization Map
<img width="1919" height="991" alt="Screenshot 2026-03-03 112222" src="https://github.com/user-attachments/assets/dae7a133-2c29-44aa-9921-d25a36a97c04" />
Ref 5: SSH Brute Force Map
<br> </br>
6. Automate Alerts and create a Ticketing System
<img width="1919" height="1113" alt="Screenshot 2026-03-15 210102" src="https://github.com/user-attachments/assets/606a74e5-1f10-4c67-9ade-3272a8eafaa6" />
Ref 6: Generated Tickets
<br> </br>
<img width="1909" height="1087" alt="Screenshot 2026-03-15 204428" src="https://github.com/user-attachments/assets/adef4214-ac00-41f3-b9f8-43a466ff605f" />
Ref 7: Resolving a Ticket
<br> </br>
7. Install Elastic Defend
<img width="1210" height="879" alt="Screenshot 2026-03-15 211557" src="https://github.com/user-attachments/assets/2498dffa-2788-4ab5-bb39-70ba07f2d9ca" />
Ref 8: Elastic Defend Removing Malware


