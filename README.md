# git-ids
Use git as an intrusion detection system for your servers


How can you make sure all your system binaries and configuration files have not been compromised by an intruder? You can of course run rkhunter or AIDE on a regular base or via cron, but this is only going to show you, that a MD5 checksum has been changed.

Using git is actually more useful than you might think. You can for example see what configuration has been changed or overwritten by an automated repository update or you can roll back to a previous working version of a specific apache vhost. If multiple system engineers work on the same machine, you will be able to evaluate what they have done and even make sure it was actually them.
