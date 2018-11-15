---
title: SDN Academic/Research Project Ideas
---

# SDN Academic/University Project Ideas

## 1.  Addressing the Flow table fullfill(flow table exhaust) issue 

	In Hardware Openflow switches, Flow table suffers from the limited storage due to the use of TCAM — on which the flow table is realized in the majority of existing equipments in industry to achieve fast forwarding.	As a result, after the flow table is full filled, the switch behavior is unexpected on both forwarding and control plane.

	The reason of the fast flow entry occupation is due to the fine-grained flow entry storage of SDN.Flow tables to be monitored regurlarly and updated with fine-grained to coarse-grained flows, which should reduce the number of flows drastically .


## 2. DDoS Detection/Mitigation

	Early detection of DDoS, and mitigation is challenging and ongoing research activity in SDN security area.

	video tutorials on the same,

	https://www.youtube.com/watch?v=8E83CSRKwCo&t=13s
	https://www.youtube.com/watch?v=g_bM780lYI4
	https://www.youtube.com/watch?v=PFShXmWJn1E



## 3. Policy based Forwarding

	Policy based forwarding enables the network wide policy, which controls the  service access based on various policy parameters such as time bounded, application specific, user specific.

	For Example:
    	-user1 allow to access Internet without any limitation
    	-user2 allow to access Internet only morning 8AM to 10AM, daily
    	-user3 allow to use the webservice(port 80) from WebServer-A 
    	-user4 can access user1,2 machines.
    	-All other access requests are denied
	such policy can be defined and modified.   


## 4. SDN BGP Speaker usecases in hybrid networks
	Some of usecase/research topics are below,
 
    - SDN BGP Router
   	- BGP Load balancing/Multipath
    - Addressing BGP Prefix/Route Hijacking issues

	relavent youtube videos:
	references:
	https://en.wikipedia.org/wiki/BGP_hijacking


## 5. QoS SDN Networks
	Some of usecase/research topics are below,

    - Bandwidth allocation/reservation for VOIP Traffic
    - Dynamic bandwidth allocation
    - DSCP Marking & Queuing based usecases
    - QoE
    - Bandwidth optimization


## 6. Firewall Implementation
    - Stateful(TCP) firewall
    - ARP Inspector(To prevent ARP Poisoning, Man in the Middle attack)
    - DNS Defender



## 7. Multicontroller environment
     - Building Fault Tolerance, Scalable, High available Multicontroller environemnt
     - Data Synchoranization in Multicontroller environment
     - Master/Slave role selection in distributed Multicontroller environment


## 8. SDN Controller security issues
	 - Compromised/hijacked/malfunctioned controller breaks the network topology.	  Identifying and removing the compromised controller is an intersting topic.
	 

## 9. Multipath/Loadbalancing in Datacenter topology

## 10. Segment Routing (MPLS)

## 11. VLAN (MAC based VLAN association)

## 12. SDN Router (L3 static routing)

---

### Contact:  

Contact us in Email : **knetsolutions2@gmail.com**

---
