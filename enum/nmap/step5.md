Sometimes, just knowing the service that is running is not enough. You may want additional information, like what kind of content the service is serving, any identifying information about the service, etc.

Fortunately, nmap can do this too. Built-in are many scripts designed to scrape additional information from enumerated services. Note this is a fairly intrusive process.

To run default scripts against the Fedora machine, add the `-sC` flag `nmap -sV -sC -p- 172.19.0.2`{{execute}}.
