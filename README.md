# Shadowsocks-ChinaDns

Using ChinaDns to cleaning DNS pollution. 

Using Shadowsocks+dnsmasq-full+ipset+firewall to get over GFW. 

Compile this project to your router, then just connect to the ssid, without any setting(except that you need a Vps Server), you and everyone using this wifi can get over GFW.

Enjoy it.

#Instruction

Copy this project to openwrt/packages.
Choose them when running: make menuconfig
Then running: make V=s

You havr to set your server first.
ssh to your router and then type the following command:

vi etc/shadowsocks.json

If you don't want to use port 1080,change /etc/firewall.user as well.

