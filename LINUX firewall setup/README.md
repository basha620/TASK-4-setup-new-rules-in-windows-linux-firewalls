
Task 4: Firewall Configuration and Testing

Objective:
To understand how firewall rules are configured and used to control network traffic.

Procedure:

1. Checked the current firewall status using UFW.
2. Listed existing firewall rules.
3. Added a firewall rule to block inbound traffic on port 23 (Telnet).
4. Tested the rule by attempting a connection to the blocked port.
5. Added a rule to allow SSH traffic on port 22.
6. Removed the test block rule to restore the original firewall configuration.

Commands Used:

* sudo ufw status verbose
* sudo ufw status numbered
* sudo ufw deny 23
* telnet localhost 23
* sudo ufw allow 22
* sudo ufw delete 1

Result:
The firewall successfully blocked traffic on port 23 and allowed traffic on port 22. The test confirmed that firewall rules can be used to control access to network services.

Conclusion:
A firewall acts as a security barrier between trusted and untrusted networks. It filters incoming and outgoing traffic based on predefined rules, allowing authorized connections while blocking unauthorized access attempts. Proper firewall configuration is an essential component of system security.
