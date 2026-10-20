# This is You have been assigned to work with an external penetration tester in an iterative purple-team scenario. The tester will be attempting to execute malware samples on a simulated internal user workstation. At the same time, you will need to configure PicoSecure's security tools to detect and prevent the malware from executing.

Following the Pyramid of Pain's ascending priority of indicators, your objective is to increase the simulated adversaries' cost of operations and chase them away for good. Each level of the pyramid allows you to detect and prevent various indicators of attack.



Sample 1 -> I used the Manage Hashes technique
- 
- I blocked/restricted the attacker's SHA1 file hash.

  [Pyramid-of-pain-summit-challange Dashboard](pyramid/hash1.png)



Sample 2 -> I used the firewall defense technique
- 
- I blocked the IP (154.35.10.113) from trying to connect to any destination
 [Pyramid-of-pain-summit-challange Dashboard](pyramid/firew.png)


Sample 3 -> I used the DNS filter defense technique
- 
- The attacker may be using a DNS connection to communicate with their (C2) server, or to upload or download files over FTP. 
- I blocked attacker from connecting to the C2 server by creating a deny rule.
  [Pyramid-of-pain-summit-challange Dashboard](pyramid/dns.png)
