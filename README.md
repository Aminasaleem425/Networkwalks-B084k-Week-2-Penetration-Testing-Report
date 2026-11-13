 Networkwalks-B084k-Week-2-Penetration-Testing-Report
Cybersecurity Lab setup Week 2
Introduction & Scope
Objective: Perform security reconnaissance, information gathering, and network scanning as part of Week 2 project requirements.
Scope: Conducted strictly within authorized boundaries targeting networkwalks.com and the local LAN subnet, backed by the official Letter of Authorization.
Module 1: Network Scanning with Zenmap
Step 1: Downloaded and installed Zenmap on the Windows PC.
Step 2: Opened Command Prompt and ran ipconfig to identify the local IP address and LAN subnet.
Step 3: Launched Zenmap, entered the local LAN subnet, and selected a Ping Scan to discover live hosts.
Step 4: Documented the active live hosts, IP addresses, and MAC addresses.
Step 5: Viewed the network topology map, read the legend, and exported the output topology in PDF format to save on the desktop.
Module 2: Footprinting with Multiple Kali Tools 
Step 1: Domain Registration Check (whois)
Opened the Kali Linux terminal and ran the whois command against the target domain: whois networkwalks.com
Retrieved domain creation details, registrar information (GoDaddy), and designated name servers.
Step 2: DNS Records Lookup (nslookup)
Executed the lookup command to resolve the target domain's IP addresses and DNS configuration: nslookup networkwalks.com
Step 3: Technology Stack Identification (whatweb)
Ran the tool to identify underlying web servers, frameworks, and CMS technologies used by the target site: whatweb networkwalks.com
Step 4: HTTP Header Analysis (curl)
Inspected the web server response headers and status codes using: curl -I https://networkwalks.com
Step 5: Web Application Firewall Detection (wafw00f)Checked if a WAF protects the web server by running: wafw00f https://networkwalks.com
Step 6: DNS Enumeration (dnsrecon)
Gathered structural DNS intelligence and discovered target subdomains using: dnsrecon -d networkwalks.com

Conclusion:
Successfully completed both required project modules (W2-PM5 Zenmap scanning and W2-PM1 Kali Linux footprinting) while adhering strictly to ethical hacking guidelines and authorization protocols.