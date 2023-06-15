enable - enter privilaged EXEC mode
configure terminal - enter global configuration mode
exit - exit current configuration mode
end - like exit
vlan 10 - create vlan with number 10
show ip interface brief - display a summary of the IP configuration and status of all interfaces
show running config - displays the current running configuration 
interface <interface> - enter iterface configuration mode
shutdown - administratively disable an interface
no shutdown - enable the interface
ip route <destination_network> <subnet_mask> <next_hop> - configure a static route on the device
show ip route - displays the IP routing table of the device

interface GigabitEthernet 0/0
ip address 192.168.0.1 255.255.255.0
no shutdown

interface Serial 0/1/0
ip address <Router1-to-Router2_IP> <subnet_mask>
no shutdown

