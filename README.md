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
![Screenshot 2023-09-13 175606](https://github.com/NAVEENKUMAR4325/InformationGathering/assets/119479566/3ec70a48-8834-4880-977b-601ef3a1863b)

## Finding IP Address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## OUTPUT:

![ping](https://github.com/NAVEENKUMAR4325/InformationGathering/assets/119479566/1e04cba2-efea-4583-a15c-fd2f9289e36d)

### Finding Hosting Company:

get further detail by using ip2location.com website.

## Output:

![Screenshot 2023-09-13 175721](https://github.com/NAVEENKUMAR4325/InformationGathering/assets/119479566/f5031815-ebb4-4fed-a006-355608b8422b)

### History of the website:

## Output:

![Screenshot 2023-09-13 180123](https://github.com/NAVEENKUMAR4325/InformationGathering/assets/119479566/f0e705e6-32d1-4317-b4a4-02d7c126759a)

## Web Server Fingerprinting:
## Netcat:
```
nc 172.17.52.118 80
```
## OUTPUT:
![image](https://github.com/NAVEENKUMAR4325/InformationGathering/assets/119479566/d1f0210b-9156-404f-8c02-76d510c1811b)

## Nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![image](https://github.com/NAVEENKUMAR4325/InformationGathering/assets/119479566/fa84cef7-ca0c-4f88-abbb-74e2010e6997)

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
![image](https://github.com/NAVEENKUMAR4325/InformationGathering/assets/119479566/28c1c032-d519-4b99-8397-4169e7f92a79)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![image](https://github.com/NAVEENKUMAR4325/InformationGathering/assets/119479566/2e014e0d-7f22-4295-99a2-ed356bf53038)

## Tracing the location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![image](https://github.com/NAVEENKUMAR4325/InformationGathering/assets/119479566/82af8c57-112c-4d1c-a315-77c101b1dae7)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![image](https://github.com/NAVEENKUMAR4325/InformationGathering/assets/119479566/1e89bc42-1570-485c-b7dd-eb7eb9b59660)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![image](https://github.com/NAVEENKUMAR4325/InformationGathering/assets/119479566/f73f452c-739c-44ad-9150-12cb1f38ed94)





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
