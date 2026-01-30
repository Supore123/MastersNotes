
**Date:** 2026-01-30
**Status:** #status/review
**Topic:** Wireshark and IP addressing

---

## Executive Summary
> Context: How we handle protocols, i.e: IP addressing, DNS propoagation and remaining set requirement: i.e: HTTP and request handling

## Theoretical Framework
 - DNS queries have two fields: **name**  and **type**
	 - Resource record is the response to a query, which returns the requirements as listed
	- DNS routing isn't always used on every launch, we cache the services most of the time
- The requirement for how interconnection operates, travelling through a set of switches.

-> BGP or Autonomous systems are responsible for the propagation through the network. This is what handles it all. 

-> HTTP is much less safe than HTTPS due to the lack of encryption of the data content. 
### Security and Certification
- digital certificates handled via TLS handshake using SHA-256 hashing for security
-
# Lab Wireshark
- Reviewing the use of wireshark and using TLS (transport layer security)
- Effectively goes through the remaining setting and handling for the client and server messaging system

Content type, version, length
Example wireshark packet
`"""`
`Frame 44: 2806 bytes on wire (22448 bits), 2806 bytes captured (22448 bits) on interface wlo1, id 0`
`Ethernet II, Src: Cisco_d8:f3:df (14:a2:a0:d8:f3:df), Dst: f8:3d:c6:74:6e:d8 (f8:3d:c6:74:6e:d8)`
`Internet Protocol Version 4, Src: 209.94.90.1, Dst: 10.97.83.13`
`Transmission Control Protocol, Src Port: 443, Dst Port: 34070, Seq: 1, Ack: 518, Len: 2740`
`Transport Layer Security`
    `TLSv1.3 Record Layer: Handshake Protocol: Server Hello`
        `Content Type: Handshake (22)`
        `Version: TLS 1.2 (0x0303)`
        `Length: 122`
        `Handshake Protocol: Server Hello`
            `Handshake Type: Server Hello (2)`
            `Length: 118`
            `Version: TLS 1.2 (0x0303)`
            `Random: a584046cb07edc27604a08ce1aca9610dff8599c223708c2e6c56052feec06a2`
            `Session ID Length: 32`
            `Session ID: cd1c7330c5856900251b62e4218854f1ee80d05bc303887e79bdecf94b116d78`
            `Cipher Suite: TLS_AES_256_GCM_SHA384 (0x1302)`
            `Compression Method: null (0)`
            `Extensions Length: 46`
            `Extension: key_share (len=36) x25519`
            `Extension: supported_versions (len=2) TLS 1.3`
            `[JA3S Fullstring: 771,4866,51-43]`
            `[JA3S: 907bf3ecef1c987c889946b737b43de8]`
    `TLSv1.3 Record Layer: Change Cipher Spec Protocol: Change Cipher Spec`
        `Content Type: Change Cipher Spec (20)`
        `Version: TLS 1.2 (0x0303)`
        `Length: 1`
        `Change Cipher Spec Message`
    `TLS segment data (2607 bytes)`

`"""`