<details>

<summary>TCP (Transmission control protocol</summary>

**TCP (Transmission Control Protocol)** is one of the main protocols in the TCP/IP suite used for communication over a network. It ensures reliable, ordered, and error-checked data delivery between applications running on hosts within a network. Here’s a breakdown of its key features:

### Key Features of TCP:
1. **Connection-Oriented:** TCP establishes a connection between the sender and receiver before transmitting data, ensuring a reliable communication channel. This is done through a process called the **three-way handshake** (SYN, SYN-ACK, ACK).
  
2. **Reliable Data Transfer:** TCP guarantees that data is delivered accurately and in the correct order. If any packets are lost or corrupted during transmission, TCP will retransmit them.

3. **Error Checking:** TCP includes error-checking mechanisms through checksums. If data is corrupted during transmission, TCP detects this and requests a retransmission.

4. **Flow Control:** TCP uses flow control to manage the rate of data transmission between the sender and receiver, preventing the sender from overwhelming the receiver with too much data at once.

5. **Congestion Control:** TCP adjusts the rate of data transmission to prevent congestion in the network. It uses algorithms like **slow start** and **congestion avoidance** to ensure optimal data flow without causing network overload.

6. **Ordered Data Transmission:** TCP ensures that data is reassembled in the correct order, even if packets arrive out of sequence.

### TCP Header Structure:
- **Source Port & Destination Port:** Used to identify the sending and receiving applications.
- **Sequence Number:** Helps in ordering the packets and tracking what data has been sent and acknowledged.
- **Acknowledgment Number:** Used to confirm the receipt of data.
- **Flags:** Control flags such as SYN, ACK, FIN, and RST help in establishing, managing, and terminating the connection.

### TCP Use Cases:
- **Web Browsing (HTTP/HTTPS)**
- **Email (SMTP, IMAP, POP3)**
- **File Transfer (FTP)**
- **Remote login (SSH, Telnet)**

In summary, TCP is a reliable protocol used for transmitting data in a controlled, ordered, and error-checked manner, making it ideal for applications that require guaranteed delivery.

</details>
