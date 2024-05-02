Kali - 	
4.246.167.214

Imp Links

https://mitre-attack.github.io/attack-navigator/
https://github.com/djadmin/awesome-bug-bounty
https://github.com/enaqx/awesome-pentest


https://book.hacktricks.xyz/welcome/readme
https://github.com/yeyintminthuhtut/Awesome-Red-Teaming
https://github.com/CyberSecurityUP/Awesome-Cloud-PenTest
https://github.com/swisskyrepo/PayloadsAllTheThings
https://github.com/danielmiessler/SecLists
https://www.vulnhub.com/

https://app.hackthebox.com/invite
https://pentesterlab.com/exercises
https://ippsec.rocks/?#
https://portswigger.net/web-security

https://github.com/RedHatInsights/secure-coding-checklist

https://github.com/RedHatInsights/secure-coding-checklist
https://github.com/RedHatInsights/secure-coding-checklist
https://github.com/jaeles-project
https://github.com/myugan/awesome-docker-security
https://github.com/devsecops/awesome-devsecops

https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet
# Day 01 (Feb - 02)
Pre assessment
-Cross site scripting
-Burp Suite
-Brute force attack, dictionary attack
Module 1
- discussion about info on target
- whois
- virustool
- subfinder
- httpx to ping domains
- cat sub.txt | httpx | newFile.txt
- eyewitness takes ss of websites
- automate: subfinder -d example.com | httpx | tee sub_example.txt (1. finds sub domiain 2. Pings automatically. 3. Cat the active subdomains)
- shodan search engine or censys
- Goolge dorking
	- site:google.com insite:login
- Open Multiple URLs to open multiple urls by pasting
- Wappalyzer
- OWASP ZAP

Cross Site Scripting
- reflected
- Stored
- DOM
- Blin XSS

XSShunter.com

vulnweb.com

broken access control using fuzzing

cvss score

ffuf -w Apache.fuzz.txt -u "url" -mc all

bugcrowd.com

dvwa -labs for cyber security

nmap - for admins to check for the devices connected to the network and to check for open ports and services and vulnerabilities
amass

leebaird/discover: Custom bash scripts used to automate various penetration testing tasks including recon, scanning, enumeration, and malicious payload creation using Metasploit. For use with Kali Linux.

--------------------------------------------------------------------------


# Day 2 (Feb - 03)
SSRF: example.com/login.php/file=image.png (LFI (Local File Intruder)| RFI(Remote File Intruder))
- image.png is in same server example.com
- can access passwd file by replacing image.png with ../../../../../../../etc/passwd
- SSRFire to automte

AWSGoat

OWASP ZAP

Nuclei : is used to send requests across targets based on a template, leading to zero false positives and providing fast scanning on a large number of hosts. Nuclei offers scanning for a variety of protocols, including TCP, DNS, HTTP, SSL, File, Whois, Websocket, Headless etc. With powerful and flexible templating, Nuclei can be used to model all kinds of security checks.

Jaeles

CSRF(Cross Site Request Forgry)

Lynis - Security Auditing tool

crawling

spidering

robots.txt file to allow or disallow crawling E.X: www.google.com/robot.txt

natas - website
--------------------------------------------------------------------------


# Day 3 (Feb - 06)

subdomain --> live --> nuclie -->dalfox --> subjs --->secrets --> ffuf
dalfox - DalFox is a powerful open source XSS scanning tool and parameter analyzer and utility that fast the process of detecting and verify XSS flaws. It comes with a powerful testing engine, many niche features for the cool hacker!
Nightingale - docker image for pentesters

XSStrike - XSStrike is a Cross Site Scripting detection suite equipped with four hand written parsers, an intelligent payload generator, a powerful fuzzing engine and an incredibly fast crawler.

allinOne

LinkFinder - A python script that finds endpoints in JavaScript files

git_dumper

dockerscan

level 9 

vAPI - Vulnerable Adversely Programmed Interface which is Self-Hostable API that mimics OWASP API Top 10 scenarios through Exercises.

crAPI - completely ridiculous API (crAPI) will help you to understand the ten most critical API security risks. crAPI is vulnerable by design, but you'll be able to safely run it to educate/train yourself.

--------------------------------------------------------------------------


# Day 4 (Feb - 07)


API Security Top 10 

https://owasp.org/www-project-api-security/

BOLA - Broken Object Level Authorization

BUA - Broken User Authentication	

Excessive Data Exposure

Lack of Resources and Rate Limiting

Broken Function Level Authorization

Mass Assignment : Binding client provided 

Injection

Improper Assests Management

Insufficient Logging and monitoring

vAPI - vAPI is Vulnerable Adversely Programmed Interface which is Self-Hostable API that mimics OWASP API Top 10 scenarios through Exercises.

kiterunner

VAPI
 
 api2 - done pitchfork attack

 JWT - Header Payload Signature

ticarpi/jwt_tool

jwt-hack

Open-Redirect-payloads

--------------------------------------------------------------------------


# Day 5 (Feb - 08)

Banner Grabbing - Getting server information

wafw00f(nmpa/scripts) command to check for firewall

SearchSploit -A command-line search tool for Exploit-DB that allows you to take a copy of the Exploit Database with you. Searchsploit is included in the Exploit Database repository on GitHub. SearchSploit is very useful for security assessments when you don’t have Internet access because it gives you the power to perform detailed offline searches for exploits in the saved Exploit-DB

nse - nmap scripting engine

maclookup to see device information

netcat

medusa

xhydra

--------------------------------------------------------------------------


# Day 6 (Feb - 09)

Greenbone

tryhackme.com

meta exploit

nessus

hackthebox

--------------------------------------------------------------------------


# Day 7 (Feb - 10)

https://owasp.org/www-project-cloud-native-application-security-top-10/

Excite
-Engage LEader/Stake holders/investor
-analyze everything inside org
-communication
-plan training

Enable
-engage leaders
-org.conflicts analysis
-training

Expand
-Promote your new adoption
-skills gap

Embed
 -Continious innovation
 -measures success
 -promote invvovation
 -training on new updates or release

 Audit
     
	Infra Audit
	  	End Devices Security(end point security)
		Virtualization security
		Patch Managment
		Configuration Management

	Prowler : an Open Source security tool to perform AWS and Azure security best practices assessments, audits, incident response, continuous monitoring, hardening and forensics readiness.
AWS VPC
 - Subnets : Breaking Network into smaller networks
 - Routing table: determines the port to which packet should be sent
 - Internet Gateway: A network node that connects two different networks that use different protocols (rules) for communicating
 - NAT:
 - Customer Gateway: (E.G VPN is a gayeway btw you and aws)
 - Security Groups:
 - VPC peering:
 - NACL:
 - Key Management System: 
 - CloudHSM - Cloud Hardware Security Module

 --------------------------------------------------------------------------


# Day 8 (Feb - 13)

Data LifeCycle
- Data Creation
- Data Storage
- Data Maintenance
- Data Usage
- Data Publications
- Data Archives
- Data Deletion

 --------------------------------------------------------------------------


# Day 9 (Feb - 14)

Bugcrowd/Hackerone/ responsible disclosure

1. Select no bounty program
2. Recon is king(TLD, 1st, 2nd, 3rd order domains, scan IPs, scan JS files, screenshots)
3. Hardcoded creds/API/secret
4. Blind XSS
5. Dorks(Google andd Github)
6. 403parser
7. directory fuzzing
8. default login (shodan censys)
spidering --> sort param --> ssrf/path traversal/idor(authorize)

AZURE
------------------------------------------------------

PaaS  - platform as service?  sql, .net service, c#

IaaS - cloud stuffs

SaaS -- Bing, XBOX, office

Regions:
Datacenter:
azure portal
Resources(services in aws)

# Day 10 (Feb - 15)

SAST - Static Application Security Testing (Using Scanner and tools)

DAST - Dynamic Application Security Testing(Using Manual Testing)

Setup 

- VMWare Workstation Player

Android Application Pentest
 - Linux Based OS
 - can run ls, rm, pwd 
 - Intially Andorid was DVM(Dalvik VM)
 - ART(Android Run Time (more secure))

 https://github.com/0xArab/diva-apk-file/blob/main/DivaApplication.apk

 https://developer.android.com/studio/releases/platform-tools

 https://ibotpeaches.github.io/Apktool/install/

 
--------------------------------------------------------------------------


# Day 12 (Feb - 20)

Tethered

Unthered (After reboot everything will be normal)

--------------------------------------------------------------------------


# Day 14 (Feb - 22)

CIS	Microsoft	SQL	Server	2019	Benchmark: http://www.itref.ir/uploads/editor/b2a398.pdf