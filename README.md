# NETWORK PERFORMANCE – SOFTWARE AND USER STATISTICS
# Kunanon Pititheerachot#10997485

Please clone all resources and put them in the main folders following from table below.

When all the files are in place please open terminal and start nagios service and apache2 service.

Nagios Core commands:
  - sudo service nagios start (to start monitoring tool process)
  - sudo service nagios restart
  - sudo service nagios stop
  - sudo service nagios status

Apache2 commands:
  - sudo service apache2 start (to start web interface for monitoring tool functions)
  - sudo service apache2 stop
  - sudo service apache2 restart

Get access to the localhost on the web browser:
  - http:127.0.0.1

Nagios account for login nagios web interface
  - ID: nagiosadmin
  - PW: nagiosadmin

Main folders
- Nagios
- Nagiosgraph
- etc


Nagios
  - bin
    - nagios
    - nagiostats
    - nrpe
  - etc
  - include
  - libexec
  - perl
  - sbin
  - share
  - var
  - etc
    - objects
    - cgi.cfg
    - htpasswd.users
    - mrtg.cfg
    - nagios.cfg
    - nagios.cfg-20150214.2233
    - nagios.cfg-20150215.1923
    - nagios.cfg~
    - nrpe.cfg
    - resource.cfg
  - include
  - libexec
  - Perl
    - bin
    - lib
    - man
  - sbin
  - share
    - contexthelp	
    - images	 
    - includes	 
    - js	 
    - locale	 
    - ssi	 
    - stats	 
    - stylesheets	 
    - woodfloor_dark-master	
    - config.inc.php	
    - index.php	
    - index.php~	
    - jsonquery.html	
    - main.php	
    - master.zip	
    - menu.html	
    - menu.html~	
    - robots.txt	
    - rss-corebanner.php	
    - rss-corefeed.html	
    - rss-corefeed.php	
    - rss-newsfeed.html	
    - rss-newsfeed.php	
    - side.php	
    - side.php~	
    - sidebar.html	
  - var
    - archives
    - nagios.log	
    - objects.cache	
    - retention.dat	
    - status.dat	












Nagiosgraph
  - bin
    - insert.pl
  - cgi
  - doc
  - etc
   -  access.conf
   -  access.conf.20150215192331
   -  datasetdb.conf
   -  datasetdb.conf.20150215192331
   -  groupdb.conf
   -  groupdb.conf.20150215192331
   -  hostdb.conf
   -  hostdb.conf.20150215192331
   -  labels.conf
   -  labels.conf.20150215192331
   -  map
   -  map.20150215192331
   -  nagiosgraph-apache.conf
   -  nagiosgraph-commands.cfg
   -  nagiosgraph-nagios.cfg
   -  nagiosgraph.conf
   -  nagiosgraph.conf.20150215192331
   -  nagiosgraph.conf~
   -  nagiosgraph_de.conf
   -  nagiosgraph_de.conf.20150215192331
   -  nagiosgraph_es.conf
   -  nagiosgraph_es.conf.20150215192331
   -  nagiosgraph_fr.conf
   -  nagiosgraph_fr.conf.20150215192331
   -  ngshared.pm
   -  rrdopts.conf
   -  rrdopts.conf.20150215192331
   -  servdb.conf
   -  servdb.conf.20150215192331
  - examples
    - graph.gif	
    - graphed-host.cfg	
    - graphed-service.cfg	
    - insert.sh	
    - map_1_3
    - map_1_4_3	
    - map_1_4_4	
    - map_1_4_5	
    - map_examples	
    - map_minimal	
    - map_mwall
    - nagiosgraph-apache.conf	
    - nagiosgraph-commands.cfg	
    - nagiosgraph-logrotate	
    - nagiosgraph-nagios.cfg	
    - nagiosgraph.1.css	
    - nagiosgraph.2.css	
    - nagiosgraph.ssi
  - share
    - nagiosgraph.css	
    - nagiosgraph.css.20150215192332	
    - nagiosgraph.js	
  - util
  - var
    - log	
    - rrd	













etc
  - apahce2
  - NetworkManagement
  - UPower
  - X11
  - acpi
  - alternatives
  - apm
  - apparmor.d
  - apparmor
  - apport
  - apt
  - aptdaemon
  - at-spi2
  - avahi
  - bash_completion.d
  - bluetooth
  - brltty
  - calendar
  - chatscripts
  - compizconfig
  - console-setup
  - cracklib
  - cron.d
  - cron.daily
  - cron.hourly
  - cron.monthly
  - cron.weekly
  - cups
  - cuphelpers
  - dbconfig-common
  - dbus-1
  - dconf
  - default
  - depmod.d
  - dhcp
  - dictionaries-common
  - dnsmasq.d
  - doc-base
  - dpkg
  - emacs
    - site-start.d
  - firefox
  - fonts
  - gconf
  - gdb
  - ghostscript
  - gnome-app-install
  - gnome
  - groff
  - grub.d
  - gtk-2.0
  - gtk-3.0
  - hp
  - action.d
  - init.d
  - init
  - initramfs-tools
  - iproute2
  - kbd
  - kernel
  - ld.so.conf.d
  - ldap
  - libnl-3
  - libreoffice
  - lightdm
  - logcheck
  - logrotate.d
  - mail
  - modprobe.d
  - modules-load.d
  - mysql
  - network
  - newt
  - obex-data-server
  - pam.d
  - pcmcia
  - pear
  - perl
    - Net
  - php5
  - pki
  - pm
  - polkit-1
  - ppp
  - profile.d
  - pulse
  - python
  - python2.7
  - python3.4
  - python3
  - radiusclient-ng
  - radiusclient
  - rc0.d
  - rc1.d
  - rc2.d
  - rc3.d
  - rc4.d
  - rc5.d
  - rc6.d
  - rcS.d
  - resolvconf
  - rsyslog.d
  - samba
  - sane.d
  - security
  - selinux
  - sensors.d
  - sgml
  - webkit-options.d
  - skel
  - snmp-mibs-downloader
  - snmp
  - speech-dispatcher
  - ssh
  - ssl
  - sudoers.d
  - sysctl.d
  - systemd
  - terminfo
  - thruk
  - thunderbird
  - udev
  - ufw
  - update-manager
  - update-motd.d
  - vim
  - wpa_supplicant
  - xdg
  - xinetd.d
  - xml
  - xul-ext
  - zabbix
  - .nagiosnrpe.cfg.swp
  - .pwd.lock
  - adduser.conf
  - aliases	
  - anacrontab	
  - apg.conf	
  - bash.bashrc	
  - bash_completion	
  - bindresvport.blacklist	
  - blkid.conf	
  - blkid.tab	
  - brlapi.key	
  - brltty.conf	
  - ca-certificates.conf	
  - ca-certificates.conf.dpkg-old	
  - checkinstallrc
  - colord.conf	
  - crontab	
  - daemon.conf	
  - debconf.conf	
  - debian_version	
  - deluser.conf	
  - drirc	
  - environment	
  - fstab	
  - fuse.conf	
  - gai.conf	
  - group	
  - group-
  - gshadow	
  - gshadow-	
  - hdparm.conf
  - host.conf	
  - hostname	
  - hosts	
  - hosts.allow	
  - hosts.deny	
  - iftab	
  - inputrc	
  - insserv.conf	
  - issue	
  - issue.net	
  - kernel-img.conf	
  - kerneloops.conf	
  - ld.so.cache	
  - ld.so.conf	
  - legal	
  - libaudit.conf	
  - lintianrc
  - locale.alias	
  - localtime	
  - login.defs	
  - logrotate.conf	
  - lsb-release	
  - ltrace.conf	
  - magic	
  - magic.mime	
  - mailcap	
  - mailcap.order	
  - manpath.config	
  - mime.types	
  - mke2fs.conf	
  - modules	
  - mrtg.cfg	
  - mtab	
  - mtab.fuselock	
  - mtools.conf	
  - nagios4	
  - nail.rc	
  - nanorc	
  - netscsid.conf	
  - networks	
  - nsswitch.conf
  - os-release	
  - pam.conf	
  - papersize	
  - passwd	
  - passwd-	
  - pnm2ppa.conf	
  - popularity-contest.conf	
  - printcap	
  - profile
  - protocols	
  - rc.local	
  - resolv.conf	
  - rmt	
  - rpcetc	
  - rsyslog.conf	
  - securetty	
  - sensors3.conf	
  - services	
  - shadow	
  - shadow-	
  - shells	
  - signond.conf	
  - subgid	
  - subgid-	
  - subuid	
  - subuid-	
  - sudoers	
  - sysctl.conf
  - timezone	
  - ucf.conf	
  - updatedb.conf	
  - upstart-xsessions	
  - usb_modeswitch.conf	
  - vshell2.conf	
  - vshell2.conf~	
  - vtrgb	
  - wgetrc
  - wodim.conf	
  - xinetd.conf	
  - zsh_command_not_found	
