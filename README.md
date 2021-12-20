# Network-Scanner
A network scanner is an important element for a network administrator as well as a penetration tester. It allows the user to map the network to find devices that are connected to the same network.

The concept of the network scanner is based on the ARP(Address resolution protocol) protocol.

![arp_request1](https://user-images.githubusercontent.com/94939477/146813462-47a9ab9e-24ba-417b-9789-a67f2216e660.jpg)

The network scanner will send the ARP request indicating who has some specific IP address, let's say "192.168.1.1", the owner of that IP address ( the target ) will automatically respond saying that he is "192.168.1.1", with that response, the MAC address will also be included in the packet, this allows us to successfully retrieve all network users' IP and MAC addresses simultaneously when we send a broadcast packet ( sending a packet to all the devices in the network ).

![hacker](https://user-images.githubusercontent.com/94939477/146815700-f73be174-d1db-4c1c-b9c1-e945c5c559fb.jpg)

Here is the output result of my network.

![building-network-scanner-using-scapy](https://user-images.githubusercontent.com/94939477/146821493-0d4ca5b9-0275-49ed-aa60-4ed25eac6c71.jpg)


