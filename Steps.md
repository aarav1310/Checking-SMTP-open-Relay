# Steps to follow 

Step 1: Go to the root terminal of your Kali environment and enter into the metasploitable server by using the command **msfconsole**

Step 2: Paste the following command in your terminal after you enter the metasploit server environment 

use auxiliary/scanner/smtp/smtp_relay

step 3: Run the following command 

> set rhosts <trget ip address> 

> run

// the above commands will set the target IP as the host and run the smtp open relay vulnerability scan. Upon completion of the execution process, you will see whether the targeted IP address has the vulnerability or not 



