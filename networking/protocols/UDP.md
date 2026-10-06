User Datagram Protocol

Connectionless protocol (unlike [[TCP]])

UDP does not gurantee delivery, if packets are lost they are just lost and not verified that they were received and are not resent

#### benefits
- Quicker than TCP so better for when speed is the priority not packet integrity
- Send directly to the destination
- No guranteed delivery
- No ordering
- No built in congestion control

#### common use cases
- DNS
- DHCP
- SNMP
- TFTP
- Video calls and VoIP
- Gaming