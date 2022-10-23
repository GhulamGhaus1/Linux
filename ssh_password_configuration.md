To change password of ssh or to change auth type to password 

 Go to /etc/ssh/sshd_config and change   **PasswordAuthentication no** to   **PasswordAuthentication yes**

Restart the SSH server for the new configuration to take effect:

**sudo /etc/init.d/ssh force-reload**

**sudo /etc/init.d/ssh restart**


To setup or change password now type :
**passwd**
