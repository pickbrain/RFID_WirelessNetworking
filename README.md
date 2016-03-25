# RFID_WirelessNetworking


Transmitter to Receiver messages:-


-1	0	-1	0	1	1	1	1
1	1	1	1	1	1	1       1
1	1	1	1	1	-1	0	-1

1	1	0	0	0	0	0	1
1	1	1	1	1	1	1	1
1	1	1	1	1	1	1	1
0	0	1	1	1	1	1	1
1	0	1	0	1	0	1	1


The message turns out to be :

-1 0 -1 	--> Preamble/Initial bits
0 1     	--> Acknowledgement
Next 16bits 1's	--> Message
-1  		--> End of message
0 -1    	--> Random bits
1 1 0 0 0 0 0 1 --> Req_RN
all the remaining-> Message
