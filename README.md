# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="897" height="544" alt="image" src="https://github.com/user-attachments/assets/5e969232-c11d-489a-9962-04bccd865932" />

### Finding Hosting Company :
<img width="1113" height="618" alt="image" src="https://github.com/user-attachments/assets/6da6bcd3-fd20-482f-87d2-94a7c3229ff5" />

<img width="1051" height="581" alt="image" src="https://github.com/user-attachments/assets/ab9c7825-04a0-4606-a66f-a58d52dda889" />

### History of the website :
<img width="1128" height="628" alt="image" src="https://github.com/user-attachments/assets/e4d57da7-7e70-4b24-8a24-3dbb100dfc5c" />

### nmap :
<img width="1245" height="410" alt="image" src="https://github.com/user-attachments/assets/1b92f227-66ae-40b7-8fac-7574a5f818ea" />

### whatweb :
<img width="892" height="721" alt="image" src="https://github.com/user-attachments/assets/9b0c725f-f200-4554-9ae2-2b47af01d60f" />

### httprint :
<img width="1364" height="688" alt="image" src="https://github.com/user-attachments/assets/a696106e-255a-48d3-881d-2ad1e882f3cb" />

### TCP traceroute :
<img width="821" height="108" alt="image" src="https://github.com/user-attachments/assets/6a8cd08a-6a77-46ca-a7a3-a40427ebd5c1" />


<img width="822" height="608" alt="image" src="https://github.com/user-attachments/assets/af98c8b4-6b4c-4b3b-a663-795834681deb" />

### UDP traceroute :
<img width="825" height="621" alt="image" src="https://github.com/user-attachments/assets/715f8644-2f98-4ae9-ae1f-2070885b2186" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
