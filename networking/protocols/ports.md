There are 65535 ports
### Port ranges
* `0-1023` Well-Known
	* Reserved for core services and systems
	* ex 80 for http or 22 for ssh
* `1024-49151` Registered ports
	* Applies to specific services and software
	* less restrictive
* `49152-65535` Dynamic and Private ports
	* Temporary ports
	* Usually used for some service then discarded

### Common Ports

| Port  | Service                     |
| ----- | --------------------------- |
| 20/21 | FTP                         |
| 22    | SSH                         |
| 23    | Telnet                      |
| 25    | SMTP                        |
| 53    | DNS                         |
| 123   | Network Time Protocol (NTP) |
| 139   | (old) SMB                   |
| 143   | IMAP                        |
| 80    | HTTP                        |
| 443   | HTTPS                       |
| 445   | SMB                         |
| 587   | SMTPS                       |
