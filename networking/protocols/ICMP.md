Internet Control Message Protocol

Unlike [[TCP]] and [[UDP]] it does **not** send any application data

#### Commonly used for:
- Error messages
- Status information
- Diagnostic information
- Testing network connectivity

#### common message types
- Echo request
	- Determine if another device is reachable (use `ping`)
- Echo reply
	- Response to echo request confirming the device is reachable
-  Destination unreachable
	- Indicates the packet could not reach the destination
- Time exceeded
	- Packet's TTL expired before reaching the destination
- Redirect
	- Informs a host about a better route to take