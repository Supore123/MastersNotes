--> Different types of attacks and operationality 

### Ip Scan

--> Using arp-scan or nmap on arp-scan --localnet to identify all devices on our network
-- ping the device after to find it and check its connectivity status

SYN Flood:
-- A syn flood is a half-open attack. The Denial of Service model operates by exploiting the handshake agreement and contiuously sending initial (SYN) connection packets. 

-  This can operate by handling this process 
- tcpreplay is used to edit the pcap files, using srcipmap dn dstipmap for the ip addresses, and the enet-dmac and enet-smac using the mac addresses.
- Then the -i wlan0 and remaining set of the syn pcap file


## IP Fragmented
- Ip fragmenting: The process of breaking down into a smaller chunks, aka fragments so that they can be transmitted over a network with a smaller maximum transmission unit. 
- The packet fragments are effectively scattered packets that are reassembled at destination.
- This occurs in the router or network and minor changes occur
#### Ip fragmented flood
- A DDoS attack aimed at saturating the bandwidth of the router and network 

#### UDP Flood
- A type of denial of service attack in which  the UDP packets are sent to a target server, effectively aiming to overwhelm a port
- This flood attacks works by exploiting the steps requried for the response system to a UDP packet

- When the server first checks to see if any programs are running on a specific port, 




