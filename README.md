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
![image](https://github.com/Prasanth9025/InformationGathering/assets/118343686/b96ec879-9345-4643-ae62-c9684dc2bfe0)

## Finding IP Address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## OUTPUT:
![image](https://github.com/Prasanth9025/InformationGathering/assets/118343686/4b3b7c72-83c3-461c-b888-e466eb7ce88a)

## Finding Hosting Company:
get further detail by using ip2location.com website.

# Output:
![image](https://github.com/Prasanth9025/InformationGathering/assets/118343686/8735854b-3773-405e-a5fa-7896e18d4488)
## History of the website:

## Output:
![image](https://github.com/Prasanth9025/InformationGathering/assets/118343686/b079de40-d883-424e-941f-5d5f418d4052)

## Web Server Fingerprinting:
## Netcat:
```
nc 172.17.52.118 80
```
## OUTPUT:
![image](https://github.com/Prasanth9025/InformationGathering/assets/118343686/efdebf8c-8ade-43c7-8de7-abc1ea51bee7)
## Nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![image](https://github.com/Prasanth9025/InformationGathering/assets/118343686/4a0da43b-2297-46f7-82f5-759c46123698)
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
![image](https://github.com/Prasanth9025/InformationGathering/assets/118343686/dbc32ed9-f5a3-4984-a2c4-0d40faf2cbcf)
## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![image](https://github.com/Prasanth9025/InformationGathering/assets/118343686/0056b123-08ea-41f9-92ea-e8172a7199ea)
## Tracing the location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![image](https://github.com/Prasanth9025/InformationGathering/assets/118343686/0fc82129-015e-4fb8-8772-55a78f298139)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![image](https://github.com/Prasanth9025/InformationGathering/assets/118343686/1e7e08d0-ce30-4854-9c59-1e1f3435255d)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![image](https://github.com/Prasanth9025/InformationGathering/assets/118343686/82fe62c7-b57d-4ba5-8c73-0779007e3651)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
