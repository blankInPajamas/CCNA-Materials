### Resources

Computer Network: It is a digital telecommunications network which allows node to share resources

Client: It is a device that accesses a service made available by a server
Server: It is a device that provides functions or services for clients

Switch:
- Have many network interfaces/ports for end hosts to connect to
- Provide connectivity to hosts within the same LAN
- do not provide connectivity btwn LANs/ over the internet.

	Examples:
	- Catalyst 9200
	- Catalyst 3650
		(Both of these are enterprise level switches)

Therefore, in order to connect LANs over the internet, we need routers.
Routers:
- Fewer network interfaces than switches
- Are used to provide connectivity btwn LANs
- Are therefore used to send data over the internet

	Examples:
		- ISR 1000
		- ISR 900
		- ISR 4000

Firewalls:
- Monitors and controls incoming and outgoing network traffic based on predefined security rules
- Can be placed 'inside' the network or 'outside the network'
- Are known as 'Next-Generation Firewalls' when they include more modern and advanced filtering capabilities

	Examples:
	- ASA5500-X
	- Firepower 2100

	These are network firewalls that are hardware devices that filter traffic btwn networks.
	Host-based firewalls are software applications that filter traffic entering and exiting a host machine, like a PC

##### Quizzes

1. **Your company wants to purchase some network hardware to which they can plug the 30 PCs in your department. Which type of network device is appropriate?**
	- Router
	- Firewall
	- ==Switch==
	- Server (It is a end host itself, not a networking device)

2. **You received a video file from your friend's Apple iPhone using AirDrop. What was his iPhone functioning as in that transaction?**
	- ==Server (Provided functions or services to the client)== 
	- Client
	- LAN

3. **What is your computer or smartphone functioning as while you watch this video?**
	- Server
	- End host (My device is a end host, but it does not define its function)
	- ==Client (Receiving a service provided by a server)==

4. **Your company wants to purchase some network hardware to connect its separate networks together. What kind of network device is appropriate?**
	- Firewall (Can connect multiple networks together, but its primary function is to control and monitor incoming and outgoing traffics)
	- Host
	- LAN
	- ==Router (Connect and forward network traffic btwn multiple networks)==

5. **Your company wants to upgrade its old network firewall that has been in use for several years to one that provides more advanced functions. What kind of firewall should they purchase?**
	- Host-based firewall
	- Next-level firewall
	- ==Next-generation firewall==
	- Top-layer firewall