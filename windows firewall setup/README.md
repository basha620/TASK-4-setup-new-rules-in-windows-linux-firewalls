Task 4: Configure and Test Firewall Rules Using Windows Defender Firewall

Objective:
To understand how firewall rules are created and used to control network traffic.

Procedure:

1. Opened Windows Defender Firewall with Advanced Security.
2. Reviewed existing inbound firewall rules.
3. Created a rule to block inbound TCP traffic on port 23 (Telnet).
4. Tested the blocked port using Telnet/PowerShell.
5. Created a rule to allow inbound TCP traffic on port 22 (SSH).
6. Removed the Telnet block rule to restore the original configuration.

Result:
The firewall successfully blocked inbound traffic on port 23 and allowed traffic on port 22. Testing confirmed that firewall rules affect network connectivity according to the configured policy.

Conclusion:
A firewall monitors and filters network traffic based on security rules. It helps protect systems from unauthorized access by allowing legitimate traffic and blocking unwanted connections.

