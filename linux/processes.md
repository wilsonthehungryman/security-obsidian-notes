
Processes can be configured to run at boot (really useful for persistence)

Processes can be ran either in the foreground or the background
- use `ctrl+z` to send a foreground process to the background
- to foreground a process type `fg`

crontab is a good way to automatically run commands or processes based on the time
- crontab starts at boot
- ex `0 */12 * * * cp -R /home/cmnatic/Documents /var/backups/` runs a backup every 12 hours
- `@reboot command` will run a command at boot
### common commands
 - `ps`
	- show running processes
	- `ps aux` shows processes for all users
- `top`
	- shows the top running processes in real time (similar to task manager in windows)
- `kill PID`
	- kill a process
- `systemctl` manage services
	- `systemctl start` start a process
	- `systemctl stop` stop a process
	- `systemctl restart` restart a process
	- `systemctl enable/disable` enable or disable a process to start at boot
	- `systemctl status` display the status for a process