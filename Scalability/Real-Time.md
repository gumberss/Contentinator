[Real-Time Delivery Architecture at Twitter](https://www.infoq.com/presentations/Real-Time-Delivery-Twitter/)

[Flannel: An Application-Level Edge Cache to Make Slack Scale](https://slack.engineering/flannel-an-application-level-edge-cache-to-make-slack-scale/)

[How Discord Stores Billions of Messages](https://discord.com/blog/how-discord-stores-billions-of-messages)
- To query for recent messages in the channel we generate a bucket range from current time to channel_id (it is also a Snowflake and has to be older than the first message). We then sequentially query partitions until enough messages are collected.

[How Discord Stores Trillions of Messages](https://discord.com/blog/how-discord-stores-trillions-of-messages)
