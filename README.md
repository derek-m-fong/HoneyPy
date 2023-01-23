# HoneyPy
Honey Pot program that detects traffic on a given port and creates a log. Also has a Snort Rule Generator and Firewall Guide.

This program should work on any operating system. If an OS can not be detected, an error may occur because it needs this information to locate the Desktop where files are saved.

It is recommended that you install telnet to test this program. You can generate traffic in other ways (SSH, borwser, etc), but Telnet tends to work the best.

Make sure you cleanly close the program with the timer. If you leave the HoneyPot open for a long period of time (ex: 7 days) but end it prematurely, you may have issues on whatever port you picked as it will still be in use. You may need to reset it to continue using it again. 

This program was created by Derek Matthew Fong, Izabella Tantillo (https://github.com/Izzy-Tantillo) and Ivan Miskic (https://www.linkedin.com/in/ivan-t-miskic/)

