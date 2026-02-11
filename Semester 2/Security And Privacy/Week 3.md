# Introduction
-> These notes are made prior to the start of the remaining lecture set i.e: before the lecture starts

--> ## Notes for the Intro to the DOS and attacks on Availability

## DOS : Denial of Service
-- DOS attacks are an attack on services 
Availability and handling. 


## Threats to availability
- i.e: Hardware failures, Malware, or DoS. 
- DoS attacks typically use a small amount of packets to disrupt or flood a system to cause the Denial of Service. This is through **Amplification**

#### Types Of Attacks
- i.e: a ping request being sent a bunch of times through a gateway causes this issue
- The use of Smurf amplification DOS attacks --> where you have multiple devices mass ping to block hardware causing this issue
-

	- Ip Spoofing, SYN Floods, DOS attacks
	- These are methods of attacking by sending mass packets to effectively block traffic at a certain point
- TCP Flood: a variant similar to SYN, but this time it is worse since it can bypass SYN flood protection proxy, but this shows the IP of the sender.
- Would like GCA AIDE access to coursework
- Might need to map historically measurements in DoS attacks -- reviewing is important for the coursework.
 - Attacking Linux OS via ssh through gateway is done by 
### How to generate DoS attacks 
- Sophisticated tools not even needed, Snort is a tool to allow this type of use.
- How to access the use of Snort
## Lab
Intrusion Detection: 
- The process of intruding onto a network -- we can determine how the information is being utilized
- This is being utilized by having a IPS (intrusion prevention system) in the middle to prevent traffic being spread like this. 

## Snort Lab
###