# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
CLIENT:
![Screenshot 2024-03-12 221638](https://github.com/arulsuriyalokeshy/2c.ARP_RARP_PROTOCOLS/assets/149130151/4ffc0246-35e2-4742-9319-c5247ac69b0d)

SERVER:
![Screenshot 2024-03-12 221708](https://github.com/arulsuriyalokeshy/2c.ARP_RARP_PROTOCOLS/assets/149130151/dfbfb0ad-103e-4f6c-ac23-6c5328281582)


## OUPUT - ARP
CLIENT:
![Screenshot 2024-03-12 221602](https://github.com/arulsuriyalokeshy/2c.ARP_RARP_PROTOCOLS/assets/149130151/86eaf2c5-c2ad-45ad-8516-94c552ad7e85)

SERVER:
![Screenshot 2024-03-12 221547](https://github.com/arulsuriyalokeshy/2c.ARP_RARP_PROTOCOLS/assets/149130151/eb0568ed-9994-4368-9642-f11c236b491c)

## PROGRAM - RARP
CLIENT:
![Screenshot 2024-03-12 222427](https://github.com/arulsuriyalokeshy/2c.ARP_RARP_PROTOCOLS/assets/149130151/4acde846-5cd1-4e89-a4b3-3a59b796d1de)


SERVER:
![Screenshot 2024-03-12 222445](https://github.com/arulsuriyalokeshy/2c.ARP_RARP_PROTOCOLS/assets/149130151/fd8ee541-3abb-4682-92da-2a9c07a6cdc8)


## OUPUT -RARP
CLIENT:
![Screenshot 2024-03-12 222404](https://github.com/arulsuriyalokeshy/2c.ARP_RARP_PROTOCOLS/assets/149130151/bd0243a5-e870-4102-9df8-2803da345df2)


SERVER:
![Screenshot 2024-03-12 222345](https://github.com/arulsuriyalokeshy/2c.ARP_RARP_PROTOCOLS/assets/149130151/c7aa1e24-2072-4c7d-9281-262a76a84698)


## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
