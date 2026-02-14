**Date:** 2026-02-11
**Status:** #status/review
**Topic:** #ml/theory

---

## Executive Summary
> Continuation for the Security overview

Security examples:

CAPTCHA is a method to verify a connection is from a human

Process of recasting this device and handling
CAPTACHS are applied to application layer DDoS 

--> Another method is source identification:
	- Find the packet source and block the IP from source.
	- Issue is that IP's can be spoofed, so how do we find packet origin?
	- So a countermeasure is to use ISP's to handle the forwarding packets
- This requires an ISP universally apply this (which is unlikely)
- So another method to solve this is to write a path into the actual network packet, where each router will add its own IP address to the packet. This allows a trace of the route, but the issue is that this will make the packets even longer. 
- So another possibility is to add a distance field into the packet, to make it clear how far the distance is between first router, end router and the distance between which. 

- This can be stored in the packet type now. This allows us to not get any issues with the connection speed. Used for fragmentation 

### BOTNETS
- Bots vs Botnets? A bot is a drone (a compromised machine) that someone can control remotely
- Implemented by a compromised machine, handled by the camera
- Attackers handle a Command Control server for handling this. 
bots are typically used in honeynets

## MalWare
- Malicious Code, which is something intended to go cause adverse effects
- Some are self spreading or non-spreading, which is either self contained or need their own types
### Virus
- A Virus is a program that can infect other programs automatically, which in the hardware->hypervisor->kernel->application layer, virus' operate in the application layer typically, but they can also operate on the hardware, where they operate on the boot level of partitions
- Antivirus's are developed, they can check its signature and compare to a known hash of virus' 
- heurisitics are a  method fo checking for the infection by reviewing the files and its compiled version
- Another method is sandboxing -- running the file in an isolated environment to see what actions it takes and see if it harms the device.
### Worms
- A self replicating computer program, which automatically spreads across a network. 
- A self constrained malware, and can spread over time, i.e: in emails or network shared devices. 
- A defence is to use techniques about how to address each of these issues, and have firewalls on the defence. This is something to check the outgoing connections or check any outgoing SMTP connections
### Trojan Horses
- A program that will need to the user to run the program, thus being software disguising its malicious actions
- 