This is unofficial snmpd 5.4.4 deb package for ubuntu 16.04

Small backround: I discovered that with net-snmp 5.7.x deb package some apps give timeout. Like supermicro5. It's a bug or limitation. Havent had time to lookup. I hope maintainers of net-snmp can do this themself in near future

After troubleshooting found that 5.4.4 is working just fine. Taken from official net-snmp 5.4.4 source. 

Official 5.4.3 ubuntu package can't be installed working normal way since so much old packages dependency. This package is built with 16.04 lts updated libs dependencies.  

Howto: 

* Be sure to uninstall current snmpd pls make proper backups of conf if needed

* This package needs following packages from deb repos: libsnmp-perl libsnmp30 python-netsnmp libsnmp-base libsnmp-perl perl-modules snmp-mibs-downloader

* Download snmpd-5.4.4.deb

* Install dpkg -i snmpd-5.4.4.deb
