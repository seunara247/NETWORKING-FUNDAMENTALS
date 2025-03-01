# NETWORKING FUNDAMENTALS

This project demonstrates key networking concepts by documenting:

- The OSI (Open System Interconnection) model with phrases to help remember the layers and real world examples for each layer.

- IP subnetting calculation using an online subnetting calculator.

- An analysis of the TCP/IP protocol suite in real-world scenerio.


## OSI (Open System Interconnection) Model Explanation

The OSI model consists of 7 layers and the numbering starts from the last one which is the physical layer. The leyers includes:

- Application Layer  - *Away*    - 7

- Presentation Layer - *Pizza*   - 6

- Session Layer - *Sausage*      - 5

- Transport Layer - *Throw*      - 4

- Network Layer - *Not*          - 3

- Data Link Layer - *Do*         - 2

- Physical  Layer - *Please*     - 1

## ACRONYM: 

Please do not throw away sausage pizza.

## EXPLANATION

I would be starting with number 1 which is physical layer

1. Physical Layer: This layer transmits raw bits over a physical medium, it is like an actual road (concrete highways) or cables (fiber optic cables) that carry vehicles (data) from one place to another.

2. Data Link Layer: This layer packages raw bits into frames and handles error detection for data travelling between adjacent network nodes, it is like a postal service that places letters into envelopes, ensuring the address is correct and that the letter is not damaged during transition.

3. Network Layer: This layer routes data packets between devices across different networks using logical addresses (like IP addresses). It works like a GPS navigation system that determines the best route for a delivery truck (data packet) to reach its destination across various cities (networks).

4. Transport Layer: This layer provides reliable, end-to-end data transfer, ensuring that packets arrive intact and in order (using order like TCP). aimagine having a courier service that only delivers your package but also confirms its receipt and redeliver if something goes wrong, it ensures that your parcel is delivered in a complete and undamaged state.

5. Session Layer: This layer manages and controls the dialogs (sessions) between computers establishing, maintaining and terminating connections. It is like a phone call system where connection is established and maintained while you communicate, and then disconnected once the call ends.

6. Presentation Layer: This layer translates data into a format the application layer can accept. This layer handles encryption, compression and data translation. it is similar to a translator who converts a conversation fron one language to another, it ensures that the data is in a readable format for the recipient and that sensitive information is encrypted.

7. Application Layer: This layer provides network services directly to end user applications like email, web browswer and so on. It is like the content of a letter that youy read, it is the final presentation of data that users interact with directly through their applications.

NOTE: every layer is built upon the previous one just like layers of onion, making sure that data is successfully transmitted from one end to the other with proper handling at each step.

##2 IP Subnetting Calculations

### Original Scenario 

*IP Address* '192.168.1.1'      
 
*Subnet Mask* '/26'

### Using an Online Subnetting Calculator:

1. Visit an online subnetting calculator (i used [IP calculator](calculator.net/ip-subnet-calculator.html))

2. Enter the IP address '192.168.1.1' and subset mask '/26'.

3. The calculator divides the netwrok into four subnets.

### Calculated Subnets:

-**Subnet 1:**

 -Network Address: 192.168.1.0
 
 -Usable Host Range: 192.168.1.1 - 192.168.1.62

 -Broadcast Address: 192.168.1.63

 -Usable Host: 62

-**Subnet 2:**

 -Network Address: 192.168.1.64
 
 -Usable Host Range: 192.168.1.65 - 192.168.1.126

 -Broadcast Address: 192.168.1.191

 -Usable Host: 62

-**Subset 3:**

 -Network Address: 192.168.1.128

 -Usable Host Range: 192.168.1.129 - 192.168.1.190

 -Broadcast Address: 192.168.1.191

 -Usable Host: 62

-**Subnet 4:**

 -Network Address: 192.168.1.192

 -Usable Host Range: 192.168.1.193 - 192.168.1.254

 -Broadcast Address: 192.168.1.255

 -Usable Host: 62

## 3. TCP(Transmisson control protocol)/IP(Internet Protocol) Protocol Suite Analysis


1. Physical & Data Link Layer: This layer transmit the raw data (bits) through calbles or Wi-Fi. IT is like a postal service using roads and vehicles to deliver a letter.

2. Network Layer: This layer routes packets using IP addresses. It is similar to a GPS system that directs a delivery truck along the best route.

3. Transport Layer: This layer ensures reliable and orderly delivery of data using TCP. It is a reliable courier service that confirms package delivery.

4. Application Layer: This layer handles high-level protocols like (HTTP) to display the web page. it is like the content of the letter that you read once it is delivered

This layered approach ensures that when you load a Web Page, each step from physical transmission to application level processing is handled systematically, making sure communication is reliable over the internet.  


