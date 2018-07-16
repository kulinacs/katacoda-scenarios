You can see services listed next to the enumerated ports on the previous output. This is not neccesarily accurate with no flags however, as nmap just matches the port number to what it expects to be running there. For example, although port 22 is traditionally running ssh, someone could easily run a web server there if they were so inclined.

nmap is capable of identifying services, however. This is done with the `-sV` flag after which nmap connects to each service and checks the service fingerprint against a database to attempt to identify it. Examine what services are actually running on the Fedora machine with `nmap -sV -p- 172.19.0.2`{{execute}}.

If done correctly, you should now see that a web server is running on port 17291.
