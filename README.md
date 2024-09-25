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
## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.


## OUTPUT:
![Screenshot 2024-09-25 084750](https://github.com/user-attachments/assets/467531ad-15f3-41d5-ad2f-e854867e657c)

## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
![Screenshot (23)](https://github.com/user-attachments/assets/b7a8269c-3fbf-490c-a3e0-e14bb9ac8b6c)

## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:
![Screenshot 2024-09-23 152156](https://github.com/user-attachments/assets/eed68598-9032-4b5b-a82b-d3da1d4452b4)

## History of the wbsite:
## Output:
https://web.archive.org/

![Screenshot 2024-09-23 152254](https://github.com/user-attachments/assets/b03729ca-85d4-4f69-bee8-d4180461184f)


## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![Screenshot (12)](https://github.com/user-attachments/assets/945b291e-cdb7-44ac-b332-a5f8977fb8b2)

## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![Screenshot (11)](https://github.com/user-attachments/assets/efada7ba-aca5-46ae-bdc2-896804116dbe)

## Whatweb:

## Output:
![Screenshot (14)](https://github.com/user-attachments/assets/29ff1497-7aa4-47d2-823f-36e92a718157)


## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.youtube.com
```
## Output:
![Screenshot (16)](https://github.com/user-attachments/assets/65ca1b44-362f-4a24-8dae-064710c677eb)

## UDP Traceroute:
```
sudo traceroute -U www.youtube.com
```
## Output:
![Screenshot (17)](https://github.com/user-attachments/assets/8f8be086-abc0-4747-b8ee-1dc891b607fe)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![Screenshot (17)](https://github.com/user-attachments/assets/38f320b2-39cb-4a18-b90c-6923652c1b1a)




## RESULT:
The information gathering techniques tools/procedure were  identified successfully
