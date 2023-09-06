# InformationGathering
Information Gathering Techniques

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
![image](https://github.com/Vasanthpushpa/InformationGathering/assets/119291100/cf23ee91-ec2a-4cf4-823d-1ab3a1a3fb46)



## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
![image](https://github.com/Vasanthpushpa/InformationGathering/assets/119291100/e0ed31f9-81f0-401a-869f-99102b2339f4)



## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:
![image](https://github.com/Vasanthpushpa/InformationGathering/assets/119291100/366d9819-7fee-4e3a-b791-809bbabbb28a)



## History of the website:
## Output:
https://web.archive.org/
![image](https://github.com/Vasanthpushpa/InformationGathering/assets/119291100/fe021253-107b-4638-9d4d-bac447cb513f)



## Web server Fingerprint:
## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![image](https://github.com/Vasanthpushpa/InformationGathering/assets/119291100/730a9855-2469-49ea-b34e-fe2f9f298690)



## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![image](https://github.com/Vasanthpushpa/InformationGathering/assets/119291100/3a342462-e354-48e9-8fa3-2b4675de38dd)



## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![image](https://github.com/Vasanthpushpa/InformationGathering/assets/119291100/74d22188-c08e-4ddd-b454-04b2e9c19a12)



## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![image](https://github.com/Vasanthpushpa/InformationGathering/assets/119291100/315035d0-0e65-4d1d-ac43-7b1b090f221d)



## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![image](https://github.com/Vasanthpushpa/InformationGathering/assets/119291100/c12b360c-b85b-4640-ba5a-4d47ecf148ab)



## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![image](https://github.com/Vasanthpushpa/InformationGathering/assets/119291100/9b9fba2b-ca16-4208-a11b-14b15d834647)



## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![image](https://github.com/Vasanthpushpa/InformationGathering/assets/119291100/5a5fda7a-79f4-47d7-ac11-25c59a6987a0)







## RESULT:
The information gathering techniques tools/procedure were  identified successfully
