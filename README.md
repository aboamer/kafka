# kafka

### pub subscribe benefit
    Decouple pub from sub
    Scaling
    backpressure as buffuring
    Reliability to resend the message if destination is down

### Kafka
    Events/messages streaming platform
    Collect messages from producers
    Store messages
    Transport to consumers
    Track message consumption

### benefits
    High throughput , low latency
    Fault tolerance
    Decouple pub from sub
    Back pressure handling, consumers need not consume all messages at once
    Horizontal Scaling
    Streaming and batching

### Kafka Message
    - Also, called as event. A unit of data that is represented as byte array. It has size limit with default 1MB.
    It can be batched by producers for efficiency

    - Message content
        Key ... not mandatory, produced by producers and don't need to be unique. Used for partitioning
        Value
        Timestamp produced by Kafka
