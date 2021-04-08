# exchange-bmc-os-info
Set OS and BMC (Baseboard Management Controller) parameters during system startup

Dependency : ipmitool

### Install :

Put ```exchange-bmc-os-info``` into ```/usr/local/sbin```, then ```chmod +x /usr/local/sbin/exchange-bmc-os-info```.

Put ```exchange-bmc-os-info.service``` into ```/etc/systemd/system```, then ```systemctl enable exchange-bmc-os-info.service```

(Taken from https://www.dell.com/support/kbdoc/fr-fr/000148573/set-os-information-in-idrac-via-ipmi)
