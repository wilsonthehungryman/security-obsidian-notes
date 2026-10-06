Transmission Control Protocol

Connection oriented transport layer protocol ([[OSI model]])

Before data is transmitted the handshake is completed (see below)

#### benefits
Unlike [[UDP]] it establishes a connection and can do things like:
- Data arrives in the correct order
- Acknowledge successful delivery
- Determine if packets were lost and retransmits them
- Close the connection once communication is complete

#### key features
- Connection orientated
- Reliable delivery
- Ordered delivery (data is reassembled in the correct sequence)
- Error checking (detects transmission errors via checksums)
- Flow control (prevents sender overwhelming a slow receiver)
- Congestion control (adjusts transmission rates as required to reduce congestion)
#### TCP flags
`SYN` Synchronize
`ACK` Acknowledge
`FIN` Finish
`RST` Reset
`PUSH` Push

#### handshake
client  ----- tcp SYN ----------> target
client <---- tcp SYN ACK ------ target
client ------ tcp ACK ----------> target