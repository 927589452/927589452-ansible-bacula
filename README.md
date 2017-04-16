*Tests*
This setup is tested with
bacula-dir in a FreeBSD Jail
bacula-sd in a FreeBSD Jail
bacula-fd on Ubuntu,Antergos,Debian Derivate

Certificates for Encryption are not autmatically generated as my own setup includes a OFFLINE (TM) system for the PKI.

*Sources*
ideas are from 
https://github.com/brodul/ansible-bacula
http://www.freebsddiary.org/bacula.php

*Bugs*:
MountPoint for the SD have to exist
SSH access to all systems and sudo are required

*ToDo*:
Verify configs ( has to be done after all roles have run)
Handler for restart / reloading the services
Add variables as toggle switches for usage of:
	-Encryption
	-VPN
