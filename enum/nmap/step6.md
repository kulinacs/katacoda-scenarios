Scans are often handy to review when working. This can be difficult if you close the terminal nmap was run in. Fortunately, nmap also supports multiple output formats, basic nmap, XML, Script Kiddie, and greppable.

To output in all formats, add the `-oA` flag followed by your filename of choice. `nmap -sV -sC -oA fedora -p- 172.19.0.2`{{execute}}
