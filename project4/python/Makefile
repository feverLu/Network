setting:
	ifconfig eth0 promisc
	iptables -A OUTPUT -p tcp --tcp-flags RST RST -j DROP
	chmod 777 rawhttpget
