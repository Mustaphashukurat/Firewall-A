# Firewall-A
Security tools
Rule Name: Block Ping Rule
Type: Inbound Rule
Protocol: ICMPv4
Action: Block
Profiles: Domain, Private, Public


Objective
Configured a firewall rule to block ICMP ping requests.

Rule Created
Blocked inbound ICMPv4 traffic.

Test Performed
Used ping localhost command.

Result
Ping request failed, showing firewall rule worked.
