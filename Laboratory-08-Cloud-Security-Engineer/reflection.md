
# Checkpoint 7 – Mission Reflection

Completing this cloud security mission helped me understand the importance of protecting a server using a host-based firewall. A host-based firewall such as UFW controls incoming and outgoing network traffic directly on the server. Even if the physical network security is breached, the firewall can still block unauthorized connections based on its configured rules.

Managing open network ports is important because every open port can provide a possible entry point for attackers. By allowing only the ports needed by the application, the server's attack surface can be reduced. In this activity, I allowed SSH for remote administration and TCP port 8080 for the Nginx web server.

Leaving a database port such as 3306 for MySQL open to the public internet is dangerous because attackers may attempt to guess passwords, exploit vulnerabilities, or access sensitive information. Database access should be restricted to authorized users and trusted application servers instead of being exposed to everyone.

This mission changed my perspective on server security because I learned that a server can become vulnerable when its network access is not properly configured. Deploying Nginx was not enough; I also needed to configure firewall rules and verify that only the required traffic was allowed. I learned to allow SSH before enabling UFW to help prevent losing remote access.

My GitHub Cloud Computing Portfolio is becoming more organized as I complete each laboratory mission. It now provides a place to document my commands, security configurations, screenshots, and reflections. These activities help me improve my Linux, Docker, firewall configuration, troubleshooting, and technical documentation skills. Overall, this mission taught me that cloud security requires careful configuration, regular monitoring, and continuous improvement.

