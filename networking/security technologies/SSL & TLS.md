Secure Socket Layer/Transport Layer Security

Cryptographic protocols used to secure comms over a network by encrypting data

TLS is the modern replacement for SSL

TLS is what we usually see in things like HTTPS

### benefits
- Encryption, TLS encrypts data so users can not see the data
- Authentication, TLS uses digital certs to verify things like we are communicating with the desired server
- Integrity, ensures data is not manipulated when sending over a network

### how it works
1. Client hello, starts a connection
2. Server hello
	1. Selects encryption settings
	2. Sends a digital cert
3. Certificate verification, client verifies the cert is valid and trusted
4. Key exchange, client and server securely establishes encryption keys
5. Encrypted communication