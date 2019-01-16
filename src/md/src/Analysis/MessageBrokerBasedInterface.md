## Technical overview of RabbitMQ based communication interface between api and anlayzer clients.

Every analyzer client should create his own exchange in 'analyzer' RabbitMq Virtual Host with the next queues:

1. index
2. analyze
3. delete
4. clean
