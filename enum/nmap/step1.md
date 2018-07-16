If your targets are not currently known (often in the case when working on a new network) nmap can help you find targets on the network. 

First, identify what network you are currently on by running `ip a`{{execute}} and identifying your IP address, in this case it is likely with `172.19.0.3`

Using your IP address, you can identify probably targets on the network. nmap accepts targets in multiple ways, but we will be using the CIDR notation. For example, if your IP address was `172.19.0.3`, you would replace the last digit with a `0` and append `/24` and run `nmap -sn 172.19.0.0/24`{{execute}}

If done correctly, you should see 3 hosts found, yourself and 2 others. In the next step, we will look at enumerating the `fedora` host.
