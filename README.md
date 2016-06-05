# raspberry-sms-gateway
SMS Gateway with UMTS Stick for sending and receiving with RaspberryPi 3 / ArchlinuxArm.

Ganz wichtig, das System muss sauber auf LANGUAGE mit utf-8 eingestellt sein.

[16:47 jcf@raspi ~] > set | grep LC
LC_ALL=en_US.utf8
LC_COLLATE=C
MAILCHECK=60

[16:47 jcf@raspi ~] > set | grep LANG
LANG=en_US.UTF-8
LANGUAGE=en_US

[16:47 jcf@raspi ~] > ls -dla /etc/localtime
lrwxrwxrwx 1 root root 33 May 31 23:31 /etc/localtime -> /usr/share/zoneinfo/Europe/Berlin

