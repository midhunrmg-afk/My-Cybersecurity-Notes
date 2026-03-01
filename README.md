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
12.cat-read file its shows in terminal .Concatenate
13.cat file1 file2 > new_file command for merge files
14.clear-clean terminal outputs
15.ps- show active processes
16.echo-print message in terminal and write text into files
17.cal-calender
18.whereis-show binary path
19.man-Explains options and usage.manual
20.nano-create file and edit 






