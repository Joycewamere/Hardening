#!/bin/bash


#Description: Centos7 Hardening
#Date: September 2020

# Disable mounting of unneeded filesystems CIS 1.1.1 and CIS 3.5
cat << EOF >> /etc/modprobe.d/CIS.conf
install cramfs /bin/true
install freevxfs /bin/true
install jffs2 /bin/true
install hfs /bin/true
install hfsplus /bin/true
install squashfs /bin/true
install udf /bin/true
install dccp /bin/true
install sctp /bin/true
install rds /bin/true
install tipc /bin/true
EOF


