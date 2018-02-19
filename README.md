# Webdav Exploit without Metasploit/Meterpreter

These are exploits created to avoid the use of Metasploit. 
While studying for OSCP in the Offsec labs, VHL, Vulnhub, etc, I tried to find ways to limit my use of Metasploit and Meterpreter shells.

The first exploit (webdavrev.py) combines a php reverse shell for Windows [found here](https://github.com/Dhayalanb/windows-php-reverse-shell), 
with a python xampp/webdav exploit [found here](https://github.com/atom-k/xampp_webdav_php). 
Please also see license info here for xampp_webdav_php: https://github.com/atom-k/xampp_webdav_php/blob/master/licence.txt

The second exploit (webdavbd.py) is a simpler modification of atom-k's exploit that only puts a CMD backdoor on the target. This is useful if there are issues with getting a shell.

Do not use these or any of the above referenced exploits on any systems in which you do not have permission to do so.

