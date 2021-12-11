## Network Security

What is network security?
                               Network security is a term that describes the security tools, tactics and security policies designed to monitor, prevent and respond to unauthorized network intrusion, while also protecting digital assets, including network traffic.
How does network security works? 
The elements of a complete, multilayered security architecture that implements network security across an organization fall into two general categories:
         Access Control  
                   Network security starts with access control. If bad actors gain access to a network, they can surveil traffic and map infrastructure. Once they have mapped infrastructure and applications, they can launch a DDoS attack or insert malware. Access control restricts the movement of bad actors throughout the network. 
      Threat Control  
               
                          
        Threat control technologies begin with the firewall and load balancer. These devices protect the network from DoS/DDoS attacks. Next, IDS/IPS counters known attacks traveling through the network. Finally, unknown malware objects traveling through the network are captured with sandbox technologies, while anomalies in network traffic that may be symptoms of a threat are caught with NTA/NDR. 
What are the key tools of network security? 
A multi-layered approach to network security implements controls at numerous points within a network to provide access control and threat control.  
Firewall : A firewall establishes a barrier between the trusted and the untrusted areas of a network. Thus, a firewall performs access control and macro-segmentation based on IP subnets. The same firewall may also perform more granular segmentation, known as micro-segmentation.
 
Load Balancer :  A load balancer distributes load based on metrics. By implementing specific mitigation techniques, a load balancer can go beyond traditional load balancing to provide the capability to absorb certain attacks, such as a volumetric DDoS attack. 

IDS/IPS  : The classic IDS/IPS is deployed behind a firewall and provides protocol analysis and signature matching on various parts of a data packet. Protocol analysis is a compliance check against the publicly declared specification of the protocol.
 
Sandbox :  A sandbox is similar to an IDS/IPS, except that it does not rely on signatures. A sandbox can emulate an end-system environment and determine if a malware object is trying, for example, to execute port scans. 
 
NTA/NDR  : NTA/NDR looks directly at traffic (or traffic records such as NetFlow) and uses machine learning algorithms and statistical techniques to evaluate anomalies and determine if a threat is present. First, NTA/NDR tries to determine a baseline. With a baseline in place, it identifies anomalies such as traffic spikes or intermittent communication.

Done by 

Yaswanth.K
 
11 December 2021


