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
