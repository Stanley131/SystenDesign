### Load Balancer 
A load balancer is a device that acts as a reverse proxy and distributes network or application traffic across a number of servers. Load balancers are used to increase capacity (concurrent users) and reliability of applications. They improve the overall performance of applications by decreasing the burden on servers associated with managing and maintaining application and network sessions, as well as by performing application-specific tasks.

- Requests are received by both types of load balancers and they are distributed to a particular server based on a configured algorithm. Some industry standard algorithms are:
	- Round robin
	- Weighted round robin
	- Least connections
	- Least response time

- Load balancing refers to efficiently distributing incoming network traffic across a group of backend servers, also known as a server farm or server pool.



- In this manner, a load balancer performs the following functions:
	- Distributes client requests or network load efficiently across multiple servers
	- Ensures high availability and reliability by sending requests only to servers that are online
	- Provides the flexibility to add or subtract servers as demand dictates



### Load Balancing Algorithms
There is a variety of load balancing methods, which use different algorithms best suited for a particular situation.

- Least Connection Method — directs traffic to the server with the fewest active connections. Most useful when there are a large number of persistent connections in the traffic unevenly distributed between the servers.
- Least Response Time Method — directs traffic to the server with the fewest active connections and the lowest average response time.
- Round Robin Method — rotates servers by directing traffic to the first available server and then moves that server to the bottom of the queue. Most useful when servers are of equal specification and there are not many persistent connections.
- IP Hash — the IP address of the client determines which server receives the request.


### Load Balancing and SSL 
Secure Sockets Layer (SSL) is the standard security technology for establishing an encrypted link between a web server and a browser. SSL traffic is often decrypted at the load balancer. When a load balancer decrypts traffic before passing the request on, it is called SSL termination. The load balancer saves the web servers from having to expend the extra CPU cycles required for decryption. This improves application performance.

However, SSL termination comes with a security concern. The traffic between the load balancers and the web servers is no longer encrypted. This can expose the application to possible attack. However, the risk is lessened when the load balancer is within the same data center as the web servers.

Another solution is the SSL pass-through. The load balancer merely passes an encrypted request to the web server. Then the web server does the decryption. This uses more CPU power on the web server. But organizations that require extra security may find the extra overhead worthwhile.


### Load Balancing and Security
Load Balancing plays an important security role as computing moves evermore to the cloud. The off-loading function of a load balancer defends an organization against distributed denial-of-service (DDoS) attacks. It does this by shifting attack traffic from the corporate server to a public cloud provider. DDoS attacks represent a large portion of cybercrime as their number and size continues to rise. Hardware defense, such as a perimeter firewall, can be costly and require significant maintenance. Software load balancers with cloud offload provide efficient and cost-effective protection.


### ADC
Eventually, load balancing took on more responsibilities with the advent of Application Delivery Controllers (ADCs). 

ADCs fall into three categories: hardware appliances, virtual appliances (essentially the software extracted from legacy hardware) and software-native load balancers. 



### Load Balancing with BIND 
- BIND is also short for Berkeley Internet Name Domain and is a popular name DNS (domain name system) server software originally designed for BSD.
-  





### What is a proxy server?
-  A proxy server is any machine that translates traffic between network or protocols. 
It is an intermediate server separating end-user clients from the destinations that
they browse. Proxy servers provide varying levels of funatinalitoes, security, and 
privacy depending on your use cases, needs, company policy. 

