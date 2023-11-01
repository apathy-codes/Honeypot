Requires paramiko:
	pip install paramiko

Change your SSH port

Linux: sudo nano /etc/ssh/sshd_config
	change #Port 22 to any other port
	save the file

Restart the SSH server:
	sudo systemctl restart ssh

Run the file, any connections will be uploaded to the terminal.
