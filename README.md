# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 
```
Developed by:Pavithra R
Register no:212222230106
```
# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

## Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 
# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion








## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 
  
  

# nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
## site:

![site](https://github.com/user-attachments/assets/c905ffd3-ad32-468e-9fc2-df1bb07c5335)

## filetype:

![filetype](https://github.com/user-attachments/assets/97a9937a-68eb-49d0-8a08-a3615d1a52fc)



## intext:

![intext](https://github.com/user-attachments/assets/d6d27de4-d54b-4afb-9f3a-09424e1425bf)



## inurl:

![ur](https://github.com/user-attachments/assets/c333aefb-706a-4065-8f4f-4d9f5ec12816)

## intitle:

![index of](https://github.com/user-attachments/assets/efeb7d6e-132f-46c4-9303-a17fd3612cef)



## link:

![link](https://github.com/user-attachments/assets/1884cf4a-b654-4a29-8b8b-0e9c5daf1eb7)



## cache:

![eg](https://github.com/user-attachments/assets/67623ff4-2356-49a8-833b-692332ccdfbb)

## DNS Enumeration:
## DNS Recon:

![45](https://github.com/user-attachments/assets/67bab4ea-279d-419d-81de-9ce312054b4a)

## dnsenum:

![46](https://github.com/user-attachments/assets/df8eae66-b930-4b1f-83b8-10aace3ddf8c)

![47](https://github.com/user-attachments/assets/b43a4b26-86cc-460a-ab7d-141c2ac4f489)



## smtp-user-enum:

![48](https://github.com/user-attachments/assets/a9cded1d-537d-4c89-8fda-bdcdecbf13fb)


## nmap –script smtp-enum-users.nse :

![49](https://github.com/user-attachments/assets/f9fec8e6-edec-481c-809b-7fc017daab40)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

