It's possible that services are running on ports not scanned by nmap by default, leaving them undetected. The ports scanned can be adjusted by the `-p` flag. 

Scan all ports on the Fedora machine by running `nmap -p- 172.19.0.2`{{execute}}.

If done correctly, you should see an additional port, `17291`, now identified.
