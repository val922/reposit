# Pentest Tools

The tools listed below are what we commonly use in penetration testing, and the tool catalog is referenced from Kali Tools, most of which are open source software. The project long-term supplementary update QAQ


## TODO

*   [x]  Directory 
*   [ ]  Browser bookmarks
*   [ ]  Install Scripts
*  	[ ] Documentation

## List
* [Information Gathering](#information-gathering)
    * [Subdomain](#Subdomain)
    * [Google Hack](#Google-Hacking)
    * [Github](#Github)
    * [SVN](#SVN)
    * [Port-Scan](#port-scan)
    * [OSINT](#OSINT)
    * [Phishing](#Phishing)
* [Vulnerability Analysis](#vulnerability-analysis)
    * [Fuzzing](#Fuzzing)
    * [Vulnerability Scan](#vulnerability-scan)
* [Web Applications](#web-applications)    
    * [CMS & Framwork Identification](#cms--framwork-identification)
    * [Web Applications Proxies](#web-applications-proxies) 
    * [Web Crawlers & Directory Brute Force](#web-crawlers--directory-brute-force)
    * [Docker Scanners](#Docker-Scanners)   
* [Database Assessment](#database-assessment)
* [Password Attacks](#password-attacks)
* [Wireless Attacks](#Wireless-Attacks)
    * [Wireless Tools](#Wireless-Tools)
* [Reverse Engineering](#Reverse-Engineering)
* [Exploitation Tools](#exploitation-tools)
    * [Vulnerability Search](#vulnerability-search)
    * [Cross-site Scripting](#cross-site-scriptingxss)
    * [Sql Injection](d#sql-injection)
    * [Command Injection](#command-injection)
    * [File Include](#file-include)
    * [File Upload vulnerability](#file-upload-vulnerability)
    * [XML External Entity Attack（XXE)](#xml-external-entity-attackxxe)
    * [Cross-site request forgery （CSRF）](#Cross-site-request-forgery-（CSRF）)
    * [Exploit Framework](#exploit-framework)
    * [Machine Learning](#Machine-Learning)
    * [Automate](#Automate)
* [Sniffing & Spoofng](#Sniffing-&-Spoofng)
* [Maintaining Access](#maintaining-access)
	* [Shell](#Shell)
    * [Web Shell](#web-shell)
    * [Privilege Escalation Auxiliary](#privilege-escalation-auxiliary) 
    * [C2](#C2)
* [Golang Sec Tools](#Golang-Sec-Tools)
* [Reporting Tools](#reporting-tools)
* [Social Engineering](#Social-Engineering)
* [System Services](#System-Services)
* [Code Audit](#code-audit) 
* [Port Forwarding & Proxies](#port-forwarding--proxies)
* [DevSecOps](#DevSecOps)
* [RootKit](#RootKit)
* [Cyber Range](#Cyber-Range)
   * [Vulnerability application](#vulnerability-application)
   * [Simulation range](#Simulation-range)
   * [CTF challenges](#CTF-challenges)
   
### Information Gathering

#### Domain Name

* [whois](https://docs.microsoft.com/en-us/sysinternals/downloads/whois) - Windows Whois performs the registration record for the domain name or IP address that you specify.

#### Subdomain

* [subDomainsBrute](https://github.com/lijiejie/subDomainsBrute) - A fast sub domain brute tool for pentesters
* [ksubdomain](https://github.com/boy-hack/ksubdomain) - Subdomain enumeration tool, asynchronous dns packets, use pcap to scan 1600,000 subdomains in 1 second
* [Sublist3r](https://github.com/aboul3la/Sublist3r) - Fast subdomains enumeration tool for penetration testers
* [OneForAll](https://github.com/shmilylty/OneForAll) - 👊 OneForAll is a powerful subdomain integration tool
* [LayerDomainFinder](https://github.com/euphrat1ca/LayerDomainFinder) - a subdomains enumeration tool by Layer

#### Google Hacking

* [GHDB](https://www.exploit-db.com/google-hacking-database/) - Google Hack Database  
* [SearchDiggity](http://www.bishopfox.com/resources/tools/google-hacking-diggity/attack-tools/) - SearchDiggity 3.1 is the primary attack tool of the Google Hacking Diggity Project 
* [Katana](https://github.com/adnane-X-tebbaa/Katana) - A Python Tool For google Hacking 
* [uDork](https://github.com/m3n0sd0n4ld/uDork) - uDork is a script written in Bash Scripting that uses advanced Google search techniques to obtain sensitive information in files or directories, find IoT devices, detect versions of web applications, and so on. 
* [Pagodo](https://github.com/opsdisk/pagodo) - pagodo (Passive Google Dork) - Automate Google Hacking Database scraping and searching .

#### Github 

* [GitHacker](https://github.com/WangYihang/GitHacker) - 🕷️ A Git source leak exploit tool that restores the entire Git repository, including data from stash, for white-box auditing and analysis of developers' mind.
* [GitGraber](https://github.com/hisxo/gitGraber) - gitGraber is a tool developed in Python3 to monitor GitHub to search and find sensitive data in real time for different online services.
* [GitMiner](https://github.com/UnkL4b/GitMiner) - Tool for advanced mining for content on Github. 
* [Gitrob](https://github.com/michenriksen/gitrob) - Reconnaissance tool for GitHub organizations. 

#### SVN

* [svnExploit](https://github.com/admintony/svnExploit) - Support for SVN source code disclosure of full version and Dump it.
* [SvnHack](https://github.com/callmefeifei/SvnHack) - SvnHack is a SVN folder disclosure exploit.
 
#### Port Scan

* [Nmap | Zenmap](https://nmap.org/) - Free and open source utility for network discovery and security auditing
* [Masscan](https://github.com/robertdavidgraham/masscan) - TCP port scanner, spews SYN packets asynchronously
* [Ports](https://github.com/nixawk/pentest-wiki/blob/master/3.Exploitation-Tools/Network-Exploitation/ports_number.md) - Common service ports and exploitations
* [Goby](https://gobies.org/) - Attack surface mapping
* [Goscan](https://github.com/marco-lancini/goscan) - Interactive Network Scanner
* [NimScan](https://github.com/elddy/NimScan) - 🚀 Fast Port Scanner 🚀
* [RustScan](https://github.com/RustScan/RustScan) - 🤖 The Modern Port Scanner 🤖
* [TXPortMap](https://github.com/4dogs-cn/TXPortMap) - Port Scanner & Banner Identify From TianXiang
* [Scaninfo](https://github.com/redtoolskobe/scaninfo) - fast scan for redtools

#### OSINT

* [theHarvester](https://github.com/laramies/theHarvester)- E-mails, subdomains and names Harvester - OSINT
* [SpiderFoot](https://github.com/smicallef/spiderfoot) - SpiderFoot automates OSINT for threat intelligence and mapping your attack surface.
* [FOCA](https://github.com/ElevenPaths/FOCA) - Tool to find metadata and hidden information in the documents. 
* [Amass](https://github.com/OWASP/Amass) - In-depth Attack Surface Mapping and Asset Discovery
* [Censys-subdomain-finder](https://github.com/christophetd/censys-subdomain-finder) - Perform subdomain enumeration using the certificate transparency logs from Censys.
* [EmailHarvester](https://github.com/maldevel/EmailHarvester) - Email addresses harvester
* [Finalrecon](https://github.com/thewhiteh4t/FinalRecon) - The Last Web Recon Tool You'll Need.
* [LittleBrother](https://github.com/lulz3xploit/LittleBrother) - Information gathering (OSINT) on a person (EU)
* [Octosuite](https://github.com/rly0nheart/octosuite) - Advanced Github OSINT Framework
* [SiteScan](https://github.com/kracer127/SiteScan) - AllinOne Information Gathering Tools

### Phishing
* [gophish](https://github.com/gophish/gophish) - Open-Source Phishing Toolkit
* [AdvPhishing](https://github.com/Ignitetch/AdvPhishing) - This is Advance Phishing Tool ! OTP PHISHING
* [SocialFish](https://github.com/UndeadSec/SocialFish) - Educational Phishing Tool & Information Collector
* [Zphisher](https://github.com/htr-tech/zphisher) - An automated phishing tool with 30+ templates. This Tool is made for educational purpose only ! Author will not be responsible for any misuse of this toolkit !
* [Nexphisher](https://github.com/htr-tech/nexphisher) - Advanced Phishing tool for Linux & Termux
 
### Vulnerability Analysis

#### Fuzzing

#### Vulnerability Scanner
* [Struts-Scan](https://github.com/Lucifer1993/struts-scan) - Struts2 vulnerability detection and utilization tools
* [Nikto](https://github.com/sullo/nikto) - Nikto is an Open Source (GPL) web server scanner which performs comprehensive tests against web servers for multiple items
* [W3af](https://github.com/andresriancho/w3af/) - Web application attack and audit framework, the open source web vulnerability scanner
* [Openvas](http://www.openvas.org/) - The world's most advanced Open Source vulnerability scanner and manager
   * [Openvas Docker](https://github.com/mikesplain/openvas-docker)
* [Archery](https://github.com/archerysec/archerysec) - Open Source Vulnerability Assessment and Management helps developers and pentesters to perform scans and manage vulnerabilities
* [Taipan](https://github.com/enkomio/Taipan) - Web application vulnerability scanner 
* [Arachni](https://github.com/Arachni/arachni) - Web Application Security Scanner Framework
* [Nuclei](https://github.com/projectdiscovery/nuclei) - Fast and customizable vulnerability scanner based on simple YAML based DSL.
* [Xray](https://github.com/chaitin/xray) - A passive-vulnerability-scanner Tool.
* [SiteScan](https://github.com/kracer127/SiteScan) - 

### Web Applications

####  CMS & Framwork Identification

* [AngelSword](https://github.com/Lucifer1993/AngelSword) - CMS vulnerability detection framework
* [WhatWeb](https://github.com/urbanadventurer/WhatWeb) - Next generation web scanner
* [Wappalyzer](https://github.com/AliasIO/Wappalyzer) - Cross-platform utility that uncovers the technologies used on websites
* [Whatruns](https://www.whatruns.com/) - A free browser extension that helps you identify technologies used on any website at the click of a button (Just for chrome)
* [WhatCMS](https://github.com/HA71/WhatCMS) - CMS Detection and Exploit Kit based on Whatcms.org API
* [CMSeeK](https://github.com/Tuhinshubhra/CMSeeK) - CMS Detection and Exploitation suite - Scan WordPress, Joomla, Drupal and over 180 other CMSs
* [EHole](https://github.com/EdgeSecurityTeam/EHole) - CMS Detection for RedTeam
CMS Detection
> Online Tools

* [Yunsee](http://www.yunsee.cn/finger.html) - Online website for to find the CMS footprint
* [Bugscaner](http://whatweb.bugscaner.com/look/) - A simple online fingerprint identification system that supports hundreds of cms source code recognition
* [WhatCMS online](https://whatcms.org/) - CMS Detection and Exploit Kit website Whatcms.org 
* [TideFinger](http://finger.tidesec.com/) -  Fingerprinter Tool from TideSec Team

#### Web Applications Proxies
* [Burpsuite](https://portswigger.net/) - Burpsuite is a graphical tool for testing Web application security
* [ZAP](https://github.com/zaproxy/zaproxy) One of the world’s most popular free security tools
* [Mitmproxy](https://github.com/mitmproxy/mitmproxy) - An interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers.
* [Broxy](https://github.com/rhaidiz/broxy) - An HTTP/HTTPS intercept proxy written in Go.

#### web browser extension

* [Hack-Tools](https://github.com/LasCC/Hack-Tools) - The all-in-one Red Team extension for Web Pentester 🛠

#### Web Crawlers & Directory Brute Force
* [Dirbrute](https://github.com/Xyntax/DirBrute) - Multi-thread WEB directory blasting tool (with dics inside)
* [Dirbuster](https://sourceforge.net/projects/dirbuster/) - DirBuster is a multi threaded java application designed to brute force directories and files names on web/application servers

#### Docker Scanners

* [Fuxi-Scanner](https://github.com/jeffzh3ng/Fuxi-Scanner) - open source network security vulnerability scanner, it comes with multiple functions.
* [Xunfeng](https://github.com/ysrc/xunfeng) - The patrol is a rapid emergency response and cruise scanning system for enterprise intranets
* [WebMap](https://github.com/KHPROG55/WebMap) - Nmap Web Dashboard and Reporting

 
### Database Assessment

### Password Attacks

* [Hydra](https://github.com/vanhauser-thc/thc-hydra) - Hydra is a parallelized login cracker which supports numerous protocols to attack
* [Medusa](http://foofus.net/goons/jmk/medusa/medusa.html) - Medusa is intended to be a speedy, massively parallel, modular, login brute-forcer
* [Sparta](http://sparta.secforce.com/): [Document](./密码攻击/Sparta（斯巴达）/Readme.md) - Network Infrastructure Penetration Testing Tool
* [Hashcat](https://github.com/hashcat/hashcat) - World's fastest and most advanced password recovery utility
* [Patator](https://github.com/lanjelot/patator) - Patator is a multi-purpose brute-forcer, with a modular design and a flexible usage.
* [HackBrowserDat](https://github.com/moonD4rk/HackBrowserData) - Decrypt passwords/cookies/history/bookmarks from the browser

### Wireless Attacks

#### Wireless Tools

* [Fern Wifi cracker](https://github.com/savio-code/fern-wifi-cracker) - Fern-Wifi-Cracker is designed to be used in testing and discovering flaws in ones own network with the aim of fixing the flaws detected
    
### Reverse Engineering

* [Ollydbg](http://www.ollydbg.de/) - OllyDbg is a 32-bit assembler level analysing debugger for Microsoft Windows

### Exploitation Tools

#### Vulnerability Search

* [SPLOITUS](https://sploitus.com) - Sploitus is а convenient central place for identifying the newest exploits and finding attacks that exploit known vulnerabilities
* [SearchSploit](https://github.com/offensive-security/exploitdb) - The official Exploit Database repository
* [Getsploit](https://github.com/vulnersCom/getsploit) - Command line utility for searching and downloading exploits

#### Cross-site Scripting（XSS）

* [BeeF](https://github.com/beefproject/beef) - The Browser Exploitation Framework Project
* [BlueLotus_XSSReceiver](https://github.com/firesunCN/BlueLotus_XSSReceiver) - XSS Receiver platform without SQL
* [xssor2](https://github.com/evilcos/xssor2) - XSS'OR - Hack with JavaScript.
* [Xsser-Varbaek](https://github.com/Varbaek/xsser) - From XSS to RCE 2.75 - Black Hat Europe Arsenal 2017 + Extras
* [Xsser-Epsylon](https://github.com/epsylon/xsser) - Cross Site "Scripter" (aka XSSer) is an automatic framework  to detect, exploit and report XSS vulnerabilities in web-based applications.
* [Xenotix](https://github.com/ajinabraham/OWASP-Xenotix-XSS-Exploit-Framework) - An advanced Cross Site Scripting (XSS) vulnerability detection and exploitation framework

####  Sql Injection

* [Sqlmap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool 
* [Sqlmate](https://github.com/s0md3v/sqlmate) - A friend of SQLmap which will do what you always expected from SQLmap
* [SQLiScanner](https://github.com/0xbug/SQLiScanner) - Automatic SQL injection with Charles and sqlmap api

#### Command Injection

* [Commix](https://github.com/commixproject/commix) - Automated All-in-One OS command injection and exploitation tool

#### File Include

* [LFIsuite](https://github.com/D35m0nd142/LFISuite) - Totally Automatic LFI Exploiter (+ Reverse Shell) and Scanner
* [Kadimus](https://github.com/P0cL4bs/Kadimus) - Kadimus is a tool to check sites to lfi vulnerability , and also exploit it
* [Shellfire](https://github.com/unix-ninja/shellfire) - Exploitation shell for exploiting LFI, RFI, and command injection vulnerabilities
* [LFIter2](https://github.com/3mrgnc3/LFIter2) - LFIter2 Local File Include (LFI) Tool - Auto File Extractor & Username Bruteforcer
* [FDsploit](https://github.com/chrispetrou/FDsploit) - File Inclusion & Directory Traversal fuzzing, enumeration & exploitation tool.

#### File Upload vulnerability

* [Fuxploider](https://github.com/almandin/fuxploider) - File upload vulnerability scanner and exploitation tool

#### XML External Entity Attack（XXE）

* [XXEinjector](https://github.com/enjoiz/XXEinjector) - Tool for automatic exploitation of XXE vulnerability using direct and different out of band methods
* [Oxml_xxe](https://github.com/BuffaloWill/oxml_xxe) - A tool for embedding XXE/XML exploits into different filetypes

#### Cross-site request forgery （CSRF）

* [Deemon](https://github.com/tgianko/deemon/) - Deemon is a tool to detect CSRF in web application

#### Exploit Framework

* [POC-T](https://github.com/Xyntax/POC-T) - Pentest Over Concurrent Toolkit
* [Pocsuite](https://github.com/knownsec/Pocsuite) - Pocsuite is an open-sourced remote vulnerability testing framework developed by the Knownsec Security Team
* [Metasploit](https://github.com/rapid7/metasploit-framework) - The world’s most used penetration testing framework
* [Venom](https://github.com/r00t-3xp10it/venom) - Shellcode generator/compiler/handler (metasploit)
* [Empire](https://github.com/EmpireProject/Empire) - Empire is a PowerShell and Python post-exploitation agent
* [Koadic](https://github.com/zerosum0x0/koadic) - Koadic C3 COM Command & Control - JScript RAT
* [Viper](https://github.com/FunnyWolf/Viper) - metasploit-framework UI manager Tools
* [MSFvenom-gui](https://github.com/ssooking/msfvenom-gui) - gui tool to create normal payload by msfvenom

#### Machine Learning

* [DeepExploit](https://github.com/13o-bbr-bbq/machine_learning_security/tree/master/DeepExploit) - Fully automatic penetration test tool using Machine Learning
* [GyoiThon](https://github.com/gyoisamurai/GyoiThon) - GyoiThon is a growing penetration test tool using Machine Learning
* [Generator](https://github.com/13o-bbr-bbq/machine_learning_security/tree/master/Generator) - Fully automatically generate numerous injection codes for web application assessment

#### Automate
* [AutoSploit](https://github.com/NullArray/AutoSploit) - Automated Mass Exploiter
* [WinPwn](https://github.com/SecureThisShit/WinPwn) - Automation for internal Windows Penetrationtest / AD-Security

### Sniffing & Spoofng

* [WireShark](https://github.com/wireshark/wireshark) - Wireshark is a network traffic analyzer, or "sniffer", for Unix and Unix-like operating systems.
* [Cain & able](http://www.oxid.it/cain.html) - Cain & Abel is a password recovery tool for Microsoft Operating Systems. 

### Maintaining Access

#### Shell

* [Goshell](https://github.com/eze-kiel/goshell) - Generate reverse shells in command line with Go !
* [Print-My-Shell](https://github.com/sameera-madushan/Print-My-Shell) - Python script wrote to automate the process of generating various reverse shells.
* [Girsh](https://github.com/nodauf/Girsh) - Automatically spawn a reverse shell fully interactive for Linux or Windows victim
* [Blueshell](https://github.com/whitehatnote/BlueShell) -  Generate a reverse shells for RedTeam 
* [Clink](http://mridgers.github.io/clink/) - Powerful Bash-style command line editing for cmd.exe
* [Natpass](https://github.com/jkstack/natpass) - A new RAT Tools, Support Web VNC and Webshell


#### Web Shell

* [Novahot](https://github.com/chrisallenlane/novahot) - A webshell framework for penetration testers.
* [Awsome-Webshells](https://github.com/abhinavprasad47/Awsome-Webshells) - Collection of reverse shells

##### PHP

* [B374K](https://github.com/b374k/b374k) - PHP Webshell with handy features
* [DAws](https://github.com/dotcppfile/DAws) - Advanced Web Shell
* [Weevely3](https://github.com/epinna/weevely3) - Weaponized web shell


##### Chopper kind Webshell

* Chopper
> Tips: The tool comes from the network, no backdoor verification, please choose it on yourself......

> Link: https://pan.baidu.com/s/1VnXkoQU-srSllG6JaY0nTA  Password: v71d

* [AntSword](https://github.com/AntSwordProject/antSword) : [Document](https://doc.u0u.us/zh-hans/index.html) - AntSword is a cross-platform website management toolkit

* [CKnife](https://github.com/Chora10/Cknife) - The cross platform webshell tool in java
> Tips: The tool comes from the network, no backdoor verification, please choose it on yourself...... 

> Link: https://pan.baidu.com/s/1QZrnWU7DUuJhiXl7u1kELw  Password: hjrh   

* [Altman](https://github.com/keepwn/Altman) - The cross platform webshell tool in .NET
* [Behinder](https://github.com/rebeyond/Behinder) - dynamic binary encryption webshell management client 
* [Godzilla](https://github.com/BeichenDream/Godzilla) - a Java tool to encrypt network traffic

#### Privilege Escalation Auxiliary

* [windows-exploit-suggester](https://github.com/GDSSecurity/Windows-Exploit-Suggester) - This tool compares a targets patch levels against the Microsoft vulnerability database in order to detect potential missing patches on the target
* [Windows-kernel-exploits](https://github.com/SecWiki/windows-kernel-exploits) - windows-kernel-exploits
* [linux-exploit-suggester-2](https://github.com/jondonas/linux-exploit-suggester-2) - Next-Generation Linux Kernel Exploit Suggester
* [Linux-kernel-exploits](https://github.com/SecWiki/linux-kernel-exploits) - linux-kernel-exploits Linux
* [BeRoot](https://github.com/AlessandroZ/BeRoot) - Privilege Escalation Project - Windows / Linux / Mac
* [PE-Linux](https://github.com/WazeHell/PE-Linux) - Linux Privilege Escalation Tool By WazeHell
* [Portia](https://github.com/SpiderLabs/portia) - Portia aims to automate a number of techniques commonly performed on internal network penetration tests after a low privileged account has been compromised.
* [PEASS-ng](https://github.com/carlospolop/PEASS-ng) - PEASS - Privilege Escalation Awesome Scripts SUITE (with colors)

#### C2

* [DeimosC2](https://github.com/DeimosC2/DeimosC2) - DeimosC2 is a Golang command and control framework for post-exploitation.
* [Sliver](https://github.com/BishopFox/sliver) - Implant framework
* [PHPSploit](https://github.com/nil0x42/phpsploit) - Full-featured C2 framework which silently persists on webserver via evil PHP oneliner 😈
* [Shad0w](https://github.com/bats3c/shad0w) - A post exploitation framework designed to operate covertly on heavily monitored environments (Win8、Win10)
* [Covenant](https://github.com/cobbr/Covenant) - Covenant is a collaborative .NET C2 framework for red teamers.
* [Emp3r0r](https://github.com/jm33-m0/emp3r0r) - linux post-exploitation framework made by linux user

### Golang Sec Tools
> Tips: Golang is a excellent cross platform language for security.

* [Naabu](https://github.com/projectdiscovery/naabu) - A fast port scanner written in go with focus on reliability and simplicity.
* [ServerScan](https://github.com/Adminisme/ServerScan) - A high concurrency network scanning and service detection tool developed by golang.

### Reporting & Collaboration

* [Vulnreport](https://github.com/salesforce/vulnreport) - Open-source pentesting management and automation platform by Salesforce Product Security 
* [Pentest-Collaboration-Framework](https://gitlab.com/invuls/pentest-projects/pcf) - Opensource, cross-platform and portable toolkit for automating routine processes when carrying out various works for testing!

### Social Engineering

### System Services

### Code Audit

* [Cloc](https://github.com/AlDanial/cloc) - cloc counts blank lines, comment lines, and physical lines of source code in many programming languages
* [Cobra](https://github.com/WhaleShark-Team/cobra) - Source Code Security Audit
* [Cobra-W](https://github.com/LoRexxar/Cobra-W) - Cobra for white hat
* [Graudit](https://github.com/wireghoul/graudit) - Grep rough audit - source code auditing tool 
* [Rips](https://github.com/ripsscanner/rips) - A static source code analyser for vulnerabilities in PHP scripts

### Port Forwarding & Proxies

* [EarthWorm](https://github.com/rootkiter/EarthWorm) - Tool for tunnel 
* [Termite](https://github.com/rootkiter/Termite/) - Tool for tunnel (Version 2) 
* [Frp](https://github.com/fatedier/frp) - A fast reverse proxy to help you expose a local server behind a NAT or firewall to the internet 
* [Nps](https://github.com/ehang-io/nps/) - A lightweight, high-performance, powerful intranet penetration proxy server, with a powerful web management terminal. 
* [Goproxy](https://github.com/snail007/goproxy) -  A high-performance, full-featured, cross platform proxy server
* [ReGeorg](https://github.com/sensepost/reGeorg) - The successor to reDuh, pwn a bastion webserver and create SOCKS proxies through the DMZ. Pivot and pwn
* [Venom](https://github.com/Dliv3/Venom) - A Multi-hop Proxy for Penetration Testers
* [Stowaway](https://github.com/ph4ntonn/Stowaway) - 👻 Stowaway -- Multi-hop Proxy Tool for pentesters
* [rport](https://github.com/cloudradar-monitoring/rport) - Manage remote systems with ease.


### DevSecOps

### RootKit

* [Beurk](https://github.com/unix-thrust/beurk) - BEURK Experimental Unix RootKit
* [Bedevil](https://github.com/naworkcaj/bdvl) - LD_PRELOAD Linux rootkit (x86 & ARM)

### Audit Tools

* [DevAudit](https://github.com/OSSIndex/DevAudit) - Open-source, cross-platform, multi-purpose security auditing tool

### Cyber Range

#### Vulnerability application

* [DVWA](https://github.com/ethicalhack3r/DVWA) - Damn Vulnerable Web Application (DVWA)
* [WebGoat](https://github.com/WebGoat/WebGoat) - WebGoat is a deliberately insecure web application maintained by OWASP designed to teach web application security lessons
* [DSVW](https://github.com/stamparm/DSVW) - DSVW is a deliberately vulnerable web application written in under 100 lines of code, created for educational purposes
* [DVWS](https://github.com/snoopysecurity/dvws) - Damn Vulnerable Web Services is an insecure web application with multiple vulnerable web service components that can be used to learn real world web service vulnerabilities
* [XVWA](https://github.com/s4n7h0/xvwa) - XVWA is a badly coded web application written in PHP/MySQL that helps security enthusiasts to learn application security
* [BWAPP](http://www.mmebvba.com/sites/bwapp/index.htm) - A buggy web application whit more than 100 vulnerabilities
* [Sqli-lab](https://github.com/Audi-1/sqli-labs) - SQLI labs to test error based, Blind boolean based, Time based
* [HackMe-SQL-Injection-Challenges](https://github.com/breakthenet/HackMe-SQL-Injection-Challenges) - Hack your friend's online MMORPG game - specific focus, sql injection opportunities
* [XSS-labs](https://github.com/paralax/xss-labs) - Small set of scripts to practice exploit XSS and CSRF vulnerabilities
* [SSRF-lab](https://github.com/m6a-UdS/ssrf-lab) - Lab for exploring SSRF vulnerabilities
* [SSRF_Vulnerable_Lab](https://github.com/incredibleindishell/SSRF_Vulnerable_Lab) - This Lab contain the sample codes which are vulnerable to Server-Side Request Forgery attack
* [LFI-labs](https://github.com/paralax/lfi-labs) - Small set of PHP scripts to practice exploiting LFI, RFI and CMD injection vulns
* [Commix-testbed](https://github.com/commixproject/commix-testbed) - A collection of web pages, vulnerable to command injection flaws
* [File-Upload-Lab](https://github.com/LunaM00n/File-Upload-Lab) - Damn Vulnerable File Upload V 1.1
* [Upload-labs](https://github.com/c0ny1/upload-labs) - A summary of all types of uploading vulnerabilities for you
* [XXE-Lab](https://github.com/c0ny1/xxe-lab) - A XXE vulnerability Demo containing language versions such as PHP, Java, python, C#, etc

#### Simulation Range

* [Fopnp](https://github.com/brandon-rhodes/fopnp/tree/m/playground) - A Network Playground for 
《Foundations of Python Network Programming》

* [CyberRange](https://github.com/secdevops-cuse/CyberRange) - The Open-Source AWS Cyber Range

#### CTF challenges
* [Vulnhub](https://www.vulnhub.com/) - VulnHub provides materials allowing anyone to gain practical hands-on experience with digital security, computer applications and network administration
* [TryHackMe](https://tryhackme.com/) - TryHackMe is a free online platform for learning cyber security, using hands-on exercises and labs, all through your browser!
* [Hackthebox](https://www.hackthebox.com/) - Hack The Box is a massive, online cybersecurity training platform, allowing individuals, companies, universities and all kinds of organizations around the world to level up their hacking skills.
* [Root Me](https://www.root-me.org/) - Root Me allows everyone to test and improve their knowledge in computer security and hacking.
