Domain Naming System

Used to translate domain names into IP addresses

### how it works
1. User wants to resolve a domain name into an IP address so it can communicate with it
2. The user's comp checks the local DNS cache, if not there continue
3. Sends a request to a DNS resolver
4. Resolver queries various DNS servers to find the correct IP address
5. The IP is returned to the user's comp
6. The user uses the IP to connect to the server

### record types
- A Record
	- Maps to an IPv4 address
- AAAA Record
	- Maps to an IPv6 address
- CNAME
	- An alias pointing to another domain
- MX Record
	- Identifies mail servers for email delivery
- TXT Record
	- Stores some information as text
- NS Record
	- Identifies authoritative DNS servers

### in pentesting
Gather information:
- Subdomains
- IP addresses
- Mail servers
- DNS records
- Publicly exposed services

### attacks
- DNS spoofing/DNS cache poisining
- DNS tunneling