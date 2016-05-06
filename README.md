# Shadowsocks-ChinaDns

Using ChinaDns to cleaning DNS pollution. 

Using Shadowsocks+dnsmasq-full+ipset+firewall to get over GFW. 

Compile this project to your router, without any setting(but you have to get a Vps Server), everyone connected to this wifi can get over GFW.

Enjoy it.

#Instruction

Copy this project to openwrt/packages.
Choose them when running: make menuconfig
Then running: make V=s

You have to set up server first.
ssh to your router and then type the following command:

vi etc/shadowsocks.json

If you don't want to use port 1080,change /etc/firewall.user as well.

