This is unofficial snmpd 5.4.4 deb package for ubuntu 16.04

Howto: 

* Download and install.

* Be sure to uninstall current snmpd pls make proper backups if needed

Small backround: I discovered that with 5.7.x deb package some apps give timeout. Like supermicro5

After troubleshooting found that 5.4.4 is working version. Taken from official net-snmp 5.4.4 source

* This package needs following packages from deb repos:

libsnmp-perl libsnmp30 python-netsnmp libsnmp-base libsnmp-perl perl-modules
