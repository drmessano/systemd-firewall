# systemd-firewall
### iptables scripts with systemd control

**Note: Repo paths are relative to root.**

1. Copy the .service and .rules files to the proper locations.

2. Enable the services:
```
systemctl enable iptables
systemctl enable ip6tables
```
3. Start the services:
```
systemctl start iptables
systemctl start ip6tables
```

ToDo: Break out the rules by task.  Currently these are common rules for an Asterisk PBX.  I will add other rules, with comments, to allow customization for a variety of needs.
