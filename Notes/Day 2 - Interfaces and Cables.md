### Notes

Switches have 24 interfaces or ports to connect end hosts like PCs. 

RJ-45 = Registered Jack
- Used on the end of copper network cable

Ethernet:
- Collection of network protocols/standards

Why do we need network protocols/standards?
- Need a common language

Bits and Bytes:
- Bits are represented by 0s and 1s
- When communicating across a copper network cable, a variation in electrical signal is interpreted by the received end as a 0 or 1. 
- Byte is a series of 8 bits.
- **Speed is measured in bits per second, because data is transmitted serially over the internet (Kbps, Mbps, Gbps, etc), not bytes per second.**

- 1 kilo bit(Kb) = 1,000 bits
- 1 megabit(Mb) = 1,000,000 bits
- 1 gigabit(Gb) = 1,000,000,000 bits
- 1 terabit (Tb) = 1,000,000,000,000 bits

**Ethernet Standards:**
- Defined in IEEE (Institute of Electrical and Electronics Engineer)

| Speed    | Common Name      | IEEE Standard | Informal Name | Maximum Length |
| -------- | ---------------- | ------------- | ------------- | -------------- |
| 10 Mbps  | Ethernet         | 802.3i        | 10BASE-T      | 100m           |
| 100 Mbps | Fast Ethernet    | 802.3u        | 100BASE-T     | 100m           |
| 1 Gbps   | Gigabit Ethernet | 802.3ab       | 1000BASE-T    | 100m           |
| 10 Gbps  | 10 Gig Ethernet  | 802.3an       | 10GBASE-T     | 100m           |
- BASE stands for baseband signaling
- T stands for twisted pair

##### Cables
The copper cables used in ethernet cables are UTP cables. Each standing for:
- U = unshielded (No metallic shield, vulnerable to electrical interference)
- T = twisted (protects against EMI: electromagnetic interference)
- P = pair

10BASE-T and 100BASE-T = 2 pairs (4 wires)

Img:
![[Full-duplex.png]]


- PC transmits data through pin 1 and 2. This is called Transmit (TX)
- PC receives data through pin 3 and 6. This is called Receive (RX).

1000BASE-T and 10GBASE-T = 4 pairs (8 wires)