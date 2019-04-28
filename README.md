Description: This will enable your attacking machine to route traffic. This 
way, when your victim machine makes a request to an external HTTP server you 
will forward the request and intercept the server’s response. This behavior 
is necessary for credential harvesting attacks. In order to use this script 
effective the attacker should configure burp suite as follows:

Step 1: Click on the proxy tab and then click on the options sub-tab.

Step 2: Click the add button and type ‘443’ for the bind port.

Step 3: Select the all interfaces radio button.

Step 4: Click on the request handling tab and check the invisible proxy 
support box.

Step 5: If you've purchased or otherwise acquired an SSL certificate you can 
configure it on the certificate tab. If not, leave those settings the way 
they are. Repeat the above steps for port ’80’ as well.
