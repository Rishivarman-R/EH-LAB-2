# InformationGathering
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
# Tested By: RISHIVARMAN R
# Reg No.:212224100050

## OUTPUT:
![Screenshot 2025-03-07 205005](https://github.com/user-attachments/assets/825b168c-a10a-4f37-90a8-4f337936c178)
# Finding IP address:
# ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

# ping saveetha.ac.in

# output:
![421965292-acff9a4a-0559-4907-af7f-421a21bb8b81](https://github.com/user-attachments/assets/7f131abe-22bd-4142-8c7f-6d6952cd2048)
# Finding Hosting Company:
# get further detail by using ip2location.com website.

# output:
![Screenshot 2025-03-07 205109](https://github.com/user-attachments/assets/109f70b4-cb17-45e0-bc3b-35a94ba8c46d)
# History of the website:
# Output:
![Screenshot 2025-03-07 205402](https://github.com/user-attachments/assets/3f83a3c0-d7e4-4446-9597-ce9e82b3cf77)
# Webserver Fingerprinting:
# Netcat: nc 172.17.52.118 80
# OUTPUT:
![421967187-423cf7a9-efb9-436e-9903-9183c84d802e](https://github.com/user-attachments/assets/d9ad940e-bce3-448f-9b1f-dd06e68de088)
# nmap:
# nmap -p 21 -sV --script=banner ftp.vim.org

# OUTPUT:
![421967549-bbd8a50d-54ec-40b1-b235-acb42508f077](https://github.com/user-attachments/assets/707acace-a038-4bcf-8989-b8a51aa6fbbd)
# Whatweb:
# whatweb infosys.com
# whatweb zoho.com
# whatweb -v -a 3 172.17.52.201
# OUTPUT:
![421967891-a9533dcf-6f64-4988-95a2-8f8b901dcc3e](https://github.com/user-attachments/assets/a88567a5-4fde-4438-be8e-95880eaacf6e)
# httprint:
# httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
# OUTPUT:
![421968245-58a2667c-30ed-4ea0-aace-6f1b10652c05](https://github.com/user-attachments/assets/3119448d-0b78-49c8-8c1e-1950ff25ed4d)
# Tracing the Location
# TCP Traceroute:
# sudo traceroute -T www.saveetha.ac.in
# OUTPUT:
![421968506-97a60031-d152-4012-a3b3-927ffa538c70](https://github.com/user-attachments/assets/02ac621f-a825-4c93-8344-1e6e2d334415)
# UDP Traceroute:
# sudo traceroute -U www.saveetha.ac.in
# OUTPUT:
![421969413-00448ac7-b0aa-4dda-807c-f85b708fb8e4](https://github.com/user-attachments/assets/9bdc782a-25be-42d3-aaaf-a0e8402b5a84)
# ICMP Traceroute:
# sudo traceroute www.saveetha.ac.in
# OUTPUT:
![421969639-c62f2894-fe72-4414-aab0-66302af2b78d](https://github.com/user-attachments/assets/622d04f2-98c9-471b-8c76-1473e06407c9)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
