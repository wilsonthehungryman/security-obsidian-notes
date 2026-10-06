**A**ddress **R**esolution **P**rotocol

A network protocol used for identifying devices on the **local** network/[[LAN]]. Determined the physical address of devices (via the MAC address)

#### process
- Sending device checks it's ARP cache, if not there it continues
- Does an ARP broadcast to all devices on the LAN, asks "who has this IP address?"
	- "Who has IP address 192.168.1.20?"
- Matching device will reply "I have this address" in an ARP reply message containing it's MAC address
	- "192.168.1.20 is at 00:1A:2B:3C:4D:5E."
- Sending device stores the IP-to-MAC mapping in the ARP cache

#### attacks
- ARP spoofing/ARP poisoning
#### components
ARP Cache
- Stores IP-to-MAC mappings, checks here first before sending a broadcast
ARP Request
- A broadcast message asking for the MAC for specific IP
ARP Reply
- A unicast response containing the MAC address