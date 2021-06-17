## Notes 14

### What’s the difference between a FIFO and a standard queue?

FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing and ensure that the order in which messages are sent and received is strictly preserved.


### How can the server be assured a message was properly received?

By the client sending back a confirmation message of some sort to the server upon receiving.

### What classic design pattern is best represented by event driven programming?

The observer pattern


### How do you test an event driven system?

Since we can basically assume that things like socket.io and the events system are thuroughly tested and working properly, we only need test our handlers.


## Vocabulary:

**FIFO Queue:** FIFO (First-In-First-Out) queues are designed to enhance messaging between applications when the order of operations and events is critical, or where duplicates can't be tolerated.


**Pub/Sub:** Publish/subscribe messaging, or pub/sub messaging, is a form of asynchronous service-to-service communication used in serverless and microservices architectures. In a pub/sub model, any message published to a topic is immediately received by all of the subscribers to the topic.