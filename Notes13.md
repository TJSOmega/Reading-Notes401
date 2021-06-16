# Notes 13

### What does it mean that web sockets are bidirectional? Why is this useful?

Information can travel from and to both server and clients. It allows a server to push messages to clients and also allows for clients to push messages back.

### Does socket.io use HTTP? Why?

Yes it does. When a websocket cannot be used it will use http instead.

### What happens when a client emits an event?

The event is picked up by any listeners on the server. Where it can be passed on if need be.

### What happens when a server emits an event?

The event is picked up by any clients listening.

### What happens if a client “misses” an event?

If a client actually misses an event then it may cause an issue in the order of how an application is run if each event is only sent out once and expected to be met with a catch or response.

### How can we mitigate this?

A good way to mitigate issues like these is to have clients respond to events with a confirmation when an event is received, before the server continues on to the next order of events.



## Vocabulary

**Socket:** A socket is one endpoint of a two-way communication link between two programs running on the network.

**Web Socket:** WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

**Socket.io:** Socket.IO enables real-time, bidirectional and event-based communication. It works on every platform, browser or device, focusing equally on reliability and speed.

**Client:** In computing, a client is a piece of computer hardware or software that accesses a service made available by a server as part of the clientserver model of computer networks.

**Server:** In computing, a server is a computer program or a device that provides functionality for other programs or devices, called "clients".

**OSI Model:** The Open Systems Interconnection model (OSI model) is a conceptual model that characterises and standardises the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology.

**TCP Model:** The TCP/IP model is a part of the Internet Protocol Suite. This model acts as a communication protocol for computer networks and connects hosts on the Internet.

**TCP:** The Transmission Control Protocol (TCP) is one of the main protocols of the Internet protocol suite. It originated in the initial network implementation in which it complemented the Internet Protocol (IP).

**UDP:** In computer networking, the User Datagram Protocol (UDP) is one of the core members of the Internet protocol suite. With UDP, computer applications can send messages, in this case referred to as datagrams, to other hosts on an Internet Protocol (IP) network.

**Packet:** In telecommunications and computer networking, a network packet is a formatted unit of data carried by a packet-switched network.
