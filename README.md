# Unified Space Data Link Protocol

Here I've created a simple implementation of USLP CCSDS protocol such as USLP TRANSFER FRAME from section 4.1 where I've implemented these 3 features 

a) Transfer Frame Primary Header (4 to 14 octets, mandatory);

b) Transfer Frame Data Field (integral number of octets, mandatory);

c) Frame Error Control Field (2 octets, optional).

and PROTOCOL PROCEDURES AT THE SENDING END from section 4.2 with implementation of MAP Packet Service and MAP Access Service in very simple way.
