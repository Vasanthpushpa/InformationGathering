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
![image](https://github.com/Bharath745/InformationGathering/assets/94508354/aae37299-680c-4731-86a1-67ca02b7f206)


## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
![image](https://github.com/Bharath745/InformationGathering/assets/94508354/c9af43a9-8839-4ee9-82d2-9a0fb7559bf2)


## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:
![image](https://github.com/Bharath745/InformationGathering/assets/94508354/930176e1-2968-4594-bbed-945afed13e13)


## History of the wbsite:
## Output:
https://web.archive.org/
![image](https://github.com/Bharath745/InformationGathering/assets/94508354/bb0e6cac-0ddf-4acb-948b-b502324f2101)


## Web server Fingerprint:
## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![image](https://github.com/Bharath745/InformationGathering/assets/94508354/defc951b-f866-42be-9d1f-c18116a4e17f)


## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![image](https://github.com/Bharath745/InformationGathering/assets/94508354/e1369e73-db6d-4445-ae2c-038451fa8ba8)


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
![image](https://github.com/Bharath745/InformationGathering/assets/94508354/aaefbcb8-b3de-4593-bd4f-c2641a89653b)


## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![image](https://github.com/Bharath745/InformationGathering/assets/94508354/f356b9e5-c3bb-44f8-b96c-b6d5ce22cdcb)


## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![image](https://github.com/Bharath745/InformationGathering/assets/94508354/1cb051dd-da76-4c79-b02b-f16976e3f31e)


## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![image](https://github.com/Bharath745/InformationGathering/assets/94508354/2f599a50-6143-412a-a2cb-7f9f6c23caec)


## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![image](https://github.com/Bharath745/InformationGathering/assets/94508354/20aa8e46-a452-444d-845f-8f23acc02f51)






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
