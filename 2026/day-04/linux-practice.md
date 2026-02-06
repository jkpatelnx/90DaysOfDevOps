# Linux Processes and Services: Hands-On Troubleshooting Practice for DevOps

###  1\. Checking Running Processes
* `ps` to list running processes  
* `top` to monitor processes in real time  
* `pgrep` to search for specific processes These commands are commonly used during performance analysis and incident investigation.

<img src="./images/linux-cmds-ps.png" width="600"> 
<img src="./images/linux-cmds-top.webp" width="600"> 
<img src="./images/linux-cmds-pgrep.png" width="600"> 


### 2\. Inspecting a systemd Service
* `systemctl status <servicen-name>` to check service health  
* `systemctl list-units` to view active services Understanding these commands is critical when diagnosing service failures or confirming whether a service is operational after configuration changes.

<img src="./images/linux-cmds-systemctl-status.png" width="600"> 
<img src="./images/linux-cmds-systemctl-list-units.png" width="600"> 


### 3\. Viewing Logs and Basic Troubleshooting
* `journalctl -u <service-name>` to view service logs
* `tail -n 50 <log-file-name>` to inspect recent log entries

<img src="./images/linux-cmds-journalctl-u-ssh.png" width="600"> 
<img src="./images/linux-cmds-tail.png" width="600"> 


### 4\. Capturing a Simple Linux Troubleshooting Flow
The troubleshooting flow included:

* Verifying the service status 
* Restarting the service when necessary
* Rechecking logs to confirm normal operation This simple flow shows how multiple Linux commands work together to diagnose and resolve issues efficiently.
    