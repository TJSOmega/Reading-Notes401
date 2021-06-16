# Notes 12

### What is the benefit of transforming data into packets?

The benefit of packets is that it allows you transfer your data over the internet to other sources.


### UDP is often refereed to as a connectionless protocol. Why is this?

Because unlike TCP that takes 3 "handshakes" in order to open a connection UDP opens a connection without confirmation being needed.


### Can a socket server application have multiple socket connections?

Yes, each time that a client connects to the server a different socket is going to be used, also if a client disconnects and reconnects a different socket is going to be used.


### Can a socket connection application be connected to multiple socket servers?

No an application is only going to connect to one server at a time.

### Can an application be both a socket server and a socket connection?

It is possible, over different ports for a server to also be a connection.



## Vocabulary:

**Observer Pattern:** The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

**Listener:** The listener is programmed to react to an input or signal by calling the event's handler.

**Event Handler:** An event handler is a callback routine that operates asynchronous ly and handles inputs received into a program ( event s).

**Event Driven Programming:** In computer programming, event-driven programming is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads.

**Event Loop:** In computer science, the event loop is a programming construct or design pattern that waits for and dispatches events or messages in a program.

**Event Queue:** An event queue is a repository where events from an application are held prior to being processed by a receiving program or system.

**Call Stack:** In computer science, a call stack is a stack data structure that stores information about the active subroutines of a computer program.

**Emit/Raise/Trigger:** The act of sending out an event that can then be picked up by a listener.

**Subscribe:** In software architecture, publish–subscribe is a messaging pattern where senders of messages, called publishers, do not program the messages to be sent directly to specific receivers, called subscribers, but instead categorize published messages into classes without knowledge of which subscribers, if any, there may be.

**database:** A database is an organized collection of data, generally stored and accessed electronically from a computer system.