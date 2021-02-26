as always nmap --help

or man nmap when stuck!


-sS   Syn Scan

-sU  UDP scan

-O   OS detection

-sV  detect the version of services running

-sC  Runs default scripts against target

-v  Increase verbose output (GOOD FOR US!!!)

-vv  EVEN MORE VERBOSE!!!!!!!!!!!!!!!!!!!!!!!!!!!

-oA <basename>  write output to a file in the 3 major formats

-oN <file>  write output to a normal format

-oG <file> write output to a grepable format

-A  AGGRESSIVE VERY LOUD DONT CARE IF IM CAUGHT MODE!!!! (Enable OS detection, version detection, script scanning, and traceroute)

-T(0-5)   Timing template  Higher is faster (more detection issuses/errors though)

-p80-100   scans only ports 80-100 (can be a single port or a range or a list)

-p-  Scan ALL ports

--script  Activate a script from nmap scripting library  (add argument to end to specify i.e.
				 --script=vuln  runs all scripts pretaining the vulns


				
When port scanning with Nmap, there are three basic scan types. These are:

    TCP Connect Scans (-sT)
    SYN "Half-open" Scans (-sS)
    UDP Scans (-sU)

Additionally there are several less common port scan types, some of which we will also cover (albeit in less detail). These are:

    TCP Null Scans (-sN)
    TCP FIN Scans (-sF)
    TCP Xmas Scans (-sX)

Most of these (with the exception of UDP scans) are used for very similar purposes, however, the way that they work differs between each scan. This means that, whilst one of the first three scans are likely to be your go-to in most situations, it's worth bearing in mind that other scan types exist.


