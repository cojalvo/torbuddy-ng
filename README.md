GENERAL:

Watch this --> https://www.youtube.com/watch?v=AedFlLSmJf8

to get a grasp what it's about. Don't forget to modify your
proxychains.conf and resolv.conf to go stealth.

Anonymous nameservers --> https://servers.opennicproject.org/


REQUIREMENTS:

Don't run the script as root.
Users running the script should modify their sudoers for example like

<username>      HOSTS = (root:root) NOPASSWD: CMDS
