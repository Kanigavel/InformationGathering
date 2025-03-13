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

## OUTPUT:
## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
## OUTPUT :
![Screenshot 2025-03-10 112530](https://github.com/user-attachments/assets/351dd0c6-59ef-4261-af80-faccfc4433b2)


Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of tesla.com

Finding Hosting Company
get further detail by using ip2location.com website.
## OUTPUT :
![Screenshot 2025-03-10 194417](https://github.com/user-attachments/assets/4c5edba1-2634-4675-a66e-4a3264a4fede)


History of the website:
## OUTPUT :
https://web.archive.org/
![Screenshot 2025-03-13 222644](https://github.com/user-attachments/assets/873dbe96-6e9d-47b6-b253-bf15fb2417c6)

# Webserver Fingerprinting:

## Netcat:
sudo nc tesla.com 80
GET / HTTP/1.1
Host: tesla.com

### OUTPUT :
![Screenshot 2025-03-13 212737](https://github.com/user-attachments/assets/3c45d9a6-69cf-46f1-b331-d2bcedba590f)

## nmap:
### OUTPUT :
![Screenshot 2025-03-13 212912](https://github.com/user-attachments/assets/11e9da36-210a-445d-9600-70f63473317c)

![Screenshot 2025-03-13 213250](https://github.com/user-attachments/assets/98550061-3805-47b7-b5c8-c2377021405a)

## Whatweb
### OUTPUT :
![Screenshot 2025-03-13 212834](https://github.com/user-attachments/assets/437c5ac8-8ec9-49d9-8710-fb62c10dbe81)
![Screenshot 2025-03-13 212814](https://github.com/user-attachments/assets/b05d9115-fe44-429a-85d5-c089c7df84ef)

## httprint
### OUTPUT :
![Screenshot 2025-03-13 224001](https://github.com/user-attachments/assets/3a964f28-c915-4626-9f5d-9c3dda22d0d2)




# Tracing the Location
TCP Traceroute:
sudo traceroute -T tesla.com
## OUTPUT :
![Screenshot 2025-03-13 224328](https://github.com/user-attachments/assets/cb50afc5-1bf6-4caf-9137-ee6f506c4dd7)


UDP Traceroute:
sudo traceroute -U tesla.com
## OUTPUT :
![Screenshot 2025-03-13 224339](https://github.com/user-attachments/assets/17ebcb09-4438-48fd-a5fd-95b0851b7d6b)


ICMP Traceroute:
sudo traceroute  tesla.com
## OUTPUT :
![Screenshot 2025-03-13 224320](https://github.com/user-attachments/assets/d67f2c19-1645-4c08-b221-df332509feec)



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
