My xmas scanner detects xmas scans on the local host interface. It sniffs for 1000 packets and detects if there has been an xmas scan. 

Test: run the python program, then, in a terminal, run nmap -sX 127.0.0.1. The python program will stop after it sniffs the packets and determines that an Xmas scan occurred. Run a regular nmap scan and it won't detect an Xmas scan. 
