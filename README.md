
# Ex-02 Information Gathering
Information Gathering Techiques

# NAME :  KAMALESH R
# REG NO : 212223230094

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
<img width="1907" height="866" alt="image" src="https://github.com/user-attachments/assets/d1163da3-1d01-45de-93c6-1ab11a4c2d70" />

### Finding Hosting Company :
<img width="1917" height="833" alt="image" src="https://github.com/user-attachments/assets/31957dbf-5eed-4c74-817f-24c6fef63d47" />

### History of the website :
<img width="1918" height="836" alt="image" src="https://github.com/user-attachments/assets/4fa62c17-c909-4e5e-9559-6ce61cb13472" />

### ping command :
<img width="1048" height="950" alt="image" src="https://github.com/user-attachments/assets/fee0e791-c179-415e-96d1-d053bd5e8fe6" />

### whois :
<img width="760" height="742" alt="479588652-79694cd4-c12c-4d63-b313-913e1506a733" src="https://github.com/user-attachments/assets/09b65619-0ca7-440e-b4a5-f8ec6808ffff" />

### netcat :
<img width="665" height="108" alt="479590058-bb93be15-acb6-4473-bc3b-590e015f712c" src="https://github.com/user-attachments/assets/6954ec15-8670-45b8-95a7-24f89e6b55f0" />

### nmap :
<img width="637" height="261" alt="479590448-37659d82-c9f5-47c1-a5bc-4baff004e2db" src="https://github.com/user-attachments/assets/4b89b4df-b5d1-4876-86d2-b8298e257310" />

### whatweb :
<img width="745" height="197" alt="479590853-928a6c89-b160-421c-add3-4dd7bd400aa0" src="https://github.com/user-attachments/assets/09fa27d3-73f2-4874-b009-378154915649" />

### httprint :
<img width="630" height="208" alt="479598583-25d1d98e-6ccd-4459-957f-c91ac4edd97e" src="https://github.com/user-attachments/assets/b671f174-01c3-4154-8801-e1b7f21dae74" />

### TCP traceroute :
<img width="747" height="394" alt="479599153-c957bd67-1b5e-42ba-baee-1fa5332cbb47" src="https://github.com/user-attachments/assets/d80ebeae-a9d1-45b2-b3ec-e2241150a1a2" />

### UDP traceroute :
<img width="731" height="527" alt="479599727-7478e1f6-9ed0-4a13-8629-fed1faa85635" src="https://github.com/user-attachments/assets/2780d89c-2653-4b30-b5e9-ff99b4aeb0ee" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
