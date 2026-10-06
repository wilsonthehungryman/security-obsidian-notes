Network security device or software that monitors ingoing and outgoing traffic

It acts as a barrier between networks

Primary purpose is to allow valid non malicious traffic while blocking suspicious or malicious requests

A firewall sits between two networks like `Internet -> firewall -> target network`

### factors
What do firewalls look at?
- Source IP address
- Destination IP address
- Port number
- Protocol ([[TCP]], [[UDP]], [[ICMP]])
- Application type
- User identity (in advanced firewalls)
Based on the factors a firewall will do the following:
- Allow the traffic
- Deny the traffic
Either way there should be a log created

### types
- Packet filtering firewall
	- Checks:
		- Source address
		- Destination address
		- Port
		- Protocol
- Stateful firewall
	-  Tracks the state of a network connection and determines if traffic belongs to an established session
- Next Generation Firewall
	- Deep packet inspection
	- Application awareness
	- IPS
	- Malware detection
	- User based policies
- Web application firewall (WAF)
	- Helps prevent attacks like [[SQLi]], [[XSS]], other malicious requests

### related tools
- [[wafw00f]]
- [[nmap]]
- 