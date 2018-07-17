# Sniffer

 $ gcc sniffer.c && sudo ./a.out

The program must be run as root user or superuser privileges. e.g. sudo ./a.out in ubuntu
The program creates raw sockets which require root access.

This creates a log.txt file in the same directory as the sniffer is running. If you would like to change the location can be changed it in the code or pass the file path as function arguments to read it while executing.

The output in the log file is something like this :



***********************TCP Packet*************************

IP Header
   |-IP Version        : 4
   |-IP Header Length  : 5 DWORDS or 20 Bytes
   |-Type Of Service   : 0
   |-IP Total Length   : 40  Bytes(Size of Packet)
   |-Identification    : 25454
   |-TTL      : 111
   |-Protocol : 6
   |-Checksum : 36991
   |-Source IP        : <Removed>
   |-Destination IP   : <Removed>


TCP Header
   |-Source Port      : 53181
   |-Destination Port : 22
   |-Sequence Number    : 2371420089
   |-Acknowledge Number : 399803918
   |-Header Length      : 5 DWORDS or 20 BYTES
   |-Urgent Flag          : 0
   |-Acknowledgement Flag : 1
   |-Push Flag            : 0
   |-Reset Flag           : 0
   |-Synchronise Flag     : 0
   |-Finish Flag          : 0
   |-Window         : 254
   |-Checksum       : 39979
   |-Urgent Pointer : 0

                        DATA Dump                         
IP Header
    45 00 00 28 63 6E 40 00 6F 06 90 7F 0A 84 93 B9         E..(cn@.o......
    64 65 15 40                                             de.@
TCP Header
    CF BD 00 16 8D 58 FF B9 17 D4 86 0E 50 10 00 FE         .....X......P...
    9C 2B 00 00                                             .+..
Data Payload

###########################################################

***********************TCP Packet*************************

IP Header
   |-IP Version        : 4
   |-IP Header Length  : 5 DWORDS or 20 Bytes
   |-Type Of Service   : 0
   |-IP Total Length   : 40  Bytes(Size of Packet)
   |-Identification    : 25455
   |-TTL      : 111
   |-Protocol : 6
   |-Checksum : 36990
   |-Source IP        : <Removed>
   |-Destination IP   : <Removed>

TCP Header
   |-Source Port      : 53181
   |-Destination Port : 22
   |-Sequence Number    : 2371420089
   |-Acknowledge Number : 399804046
   |-Header Length      : 5 DWORDS or 20 BYTES
   |-Urgent Flag          : 0
   |-Acknowledgement Flag : 1
   |-Push Flag            : 0
   |-Reset Flag           : 0
   |-Synchronise Flag     : 0
   |-Finish Flag          : 0
   |-Window         : 254
   |-Checksum       : 39851
   |-Urgent Pointer : 0

                        DATA Dump                         
IP Header
    45 00 00 28 63 6F 40 00 6F 06 90 7E 0A 84 93 B9         E..(co@.o..~....
    64 65 15 40                                             de.@
TCP Header
    CF BD 00 16 8D 58 FF B9 17 D4 86 8E 50 10 00 FE         .....X......P...
    9B AB 00 00                                             ....
Data Payload

###########################################################

***********************TCP Packet*************************

IP Header
   |-IP Version        : 4
   |-IP Header Length  : 5 DWORDS or 20 Bytes
   |-Type Of Service   : 0
   |-IP Total Length   : 104  Bytes(Size of Packet)
   |-Identification    : 25456
   |-TTL      : 111
   |-Protocol : 6
   |-Checksum : 36925
   |-Source IP        : <Removed>
   |-Destination IP   : <Removed>


TCP Header
   |-Source Port      : 53181
   |-Destination Port : 22
   |-Sequence Number    : 2371420089
   |-Acknowledge Number : 399804046
   |-Header Length      : 5 DWORDS or 20 BYTES
   |-Urgent Flag          : 0
   |-Acknowledgement Flag : 1
   |-Push Flag            : 1
   |-Reset Flag           : 0
   |-Synchronise Flag     : 0
   |-Finish Flag          : 0
   |-Window         : 254
   |-Checksum       : 31218
   |-Urgent Pointer : 0

                        DATA Dump                         
IP Header
    45 00 00 68 63 70 40 00 6F 06 90 3D 0A 84 93 B9         E..hcp@.o..=....
    64 65 15 40                                             de.@
TCP Header
    CF BD 00 16 8D 58 FF B9 17 D4 86 8E 50 18 00 FE         .....X......P...
    79 F2 00 00                                             y...
Data Payload
    20 00 EF 16 90 CE 07 06 7A BA 05 5D EE 14 42 F1          .......z..]..B.
    4F 36 24 C3 D0 22 7D BE 2D D3 87 D6 E2 4E B3 78         O6$.."}.-....N.x
    5B A0 5D 47 0A 88 85 E9 7F F0 67 3A 91 A1 E6 70         [.]G.....g:...p
    5E 53 53 51 B1 8E 02 DE E3 73 F1 21 6C 9D 6C 40         ^SSQ.....s.!l.l@

###########################################################

***********************TCP Packet*************************

IP Header
   |-IP Version        : 4
   |-IP Header Length  : 5 DWORDS or 20 Bytes
   |-Type Of Service   : 0
   |-IP Total Length   : 40  Bytes(Size of Packet)
   |-Identification    : 25457
   |-TTL      : 111
   |-Protocol : 6
   |-Checksum : 36988
   |-Source IP        : <Removed>
   |-Destination IP   : <Removed>

TCP Header
   |-Source Port      : 53181
   |-Destination Port : 22
   |-Sequence Number    : 2371420153
   |-Acknowledge Number : 399804110
   |-Header Length      : 5 DWORDS or 20 BYTES
   |-Urgent Flag          : 0
   |-Acknowledgement Flag : 1
   |-Push Flag            : 0
   |-Reset Flag           : 0
   |-Synchronise Flag     : 0
   |-Finish Flag          : 0
   |-Window         : 254
   |-Checksum       : 39723
   |-Urgent Pointer : 0

                        DATA Dump                         
IP Header
    45 00 00 28 63 71 40 00 6F 06 90 7C 0A 84 93 B9         E..(cq@.o..|....
    64 65 15 40                                             de.@
TCP Header
    CF BD 00 16 8D 58 FF F9 17 D4 86 CE 50 10 00 FE         .....X......P...
    9B 2B 00 00                                             .+..
Data Payload

###########################################################

***********************TCP Packet*************************

IP Header
   |-IP Version        : 4
   |-IP Header Length  : 5 DWORDS or 20 Bytes
   |-Type Of Service   : 0
   |-IP Total Length   : 104  Bytes(Size of Packet)
   |-Identification    : 25458
   |-TTL      : 111
   |-Protocol : 6
   |-Checksum : 36923
   |-Source IP        : <Removed>
   |-Destination IP   : <Removed>

TCP Header
   |-Source Port      : 53181
   |-Destination Port : 22
   |-Sequence Number    : 2371420153
   |-Acknowledge Number : 399804110
   |-Header Length      : 5 DWORDS or 20 BYTES
   |-Urgent Flag          : 0
   |-Acknowledgement Flag : 1
   |-Push Flag            : 1
   |-Reset Flag           : 0
   |-Synchronise Flag     : 0
   |-Finish Flag          : 0
   |-Window         : 254
   |-Checksum       : 21087
   |-Urgent Pointer : 0

                        DATA Dump                         
IP Header
    45 00 00 68 63 72 40 00 6F 06 90 3B 0A 84 93 B9         E..hcr@.o..;....
    64 65 15 40                                             de.@
TCP Header
    CF BD 00 16 8D 58 FF F9 17 D4 86 CE 50 18 00 FE         .....X......P...
    52 5F 00 00                                             R_..
Data Payload
    EC 93 14 03 D3 46 80 3C DD F8 30 33 24 71 77 2C         .....F€<..03$qw,
    1F 8F 61 30 74 24 D5 AA 16 F7 A6 29 9C 13 23 94         ..a0t$.....)..#.
    83 90 E4 7A 42 04 D3 E5 9D D1 4E 9B 77 78 FC C5         ...zB.....N.wx..
    E0 F3 4B AF 0E 3C 02 F5 35 F2 A8 4D AA 61 5E 32         ..K..<..5..M.a^2

###########################################################

***********************TCP Packet*************************

IP Header
   |-IP Version        : 4
   |-IP Header Length  : 5 DWORDS or 20 Bytes
   |-Type Of Service   : 0
   |-IP Total Length   : 40  Bytes(Size of Packet)
   |-Identification    : 25459
   |-TTL      : 111
   |-Protocol : 6
   |-Checksum : 36986
   |-Source IP        : <Removed>
   |-Destination IP   : <Removed>

TCP Header
   |-Source Port      : 53181
   |-Destination Port : 22
   |-Sequence Number    : 2371420217
   |-Acknowledge Number : 399804174
   |-Header Length      : 5 DWORDS or 20 BYTES
   |-Urgent Flag          : 0
   |-Acknowledgement Flag : 1
   |-Push Flag            : 0
   |-Reset Flag           : 0
   |-Synchronise Flag     : 0
   |-Finish Flag          : 0
   |-Window         : 253
   |-Checksum       : 39596
   |-Urgent Pointer : 0

                        DATA Dump                         
IP Header
    45 00 00 28 63 73 40 00 6F 06 90 7A 0A 84 93 B9         E..(cs@.o..z....
    64 65 15 40                                             de.@
TCP Header
    CF BD 00 16 8D 59 00 39 17 D4 87 0E 50 10 00 FD         .....Y.9....P...
                                      
