#OpenstackCinderbackup

This script takes use cinder to take backup of all non-bootable volumes of shutoff VMs in Openstack and send email to mailid if provided

Usage:

python OpenstackCinderbackup.py username  password "http://ip:port/v2.0" "mailid"
