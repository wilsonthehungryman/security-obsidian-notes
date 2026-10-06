Dynamic Host Configuration Protocol

Automatically assigns an IP address to a device when they connect to the network

An alternative to manually assigning IPs to every device on the network

### what it can assign
- IP address
- Subnet mask
- Default gateway
- DNS sever address
- Lease time

### how it works
1. Discover, client broadcasts a request asking for the DHCP server (usually a router)
2. Offer, the DHCP server responds with a IP address the client can use
3. Request, the client requests the offered address
4. Ack, the DHCP server acknowledges the request
5. Client is now assigned an IP address on the network

### attacks
- Rogue DHCP attacks
- DHCP starvation attacks