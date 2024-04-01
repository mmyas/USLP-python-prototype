# Unified Space Data Link Protocol

Here I've created a simple implementation of USLP CCSDS protocol such as USLP TRANSFER FRAME from section 4.1 where I've implemented these 3 features 

a) Transfer Frame Primary Header (4 to 14 octets, mandatory);

b) Transfer Frame Data Field (integral number of octets, mandatory);

c) Frame Error Control Field (2 octets, optional).

and PROTOCOL PROCEDURES AT THE SENDING END from section 4.2 with implementation of MAP Packet Service and MAP Access Service in very simple way.

Assuming a simplified version, I'm dealing with a single MAP channel and focus on segmenting data into smaller packets, each with a basic header. I've added a basic QoS parameter to each MAPA_SDU to prioritize packets.

First run the receiver code on one desktop and then run the sender code on another desktop with proper host and port ID for the connection to be established between the two desktop.

host Id for a desktop can be found at command prompt by type "ipconfig" and the active port can be found by typing "netstat -a -b" in the command prompt that gives all active connections and listening ports, along with the executable names of the services or processes using them.



