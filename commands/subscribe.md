@complexity

O(N) where N is the number of channels to subscribe to.

Subscribes the client to the specified channels.

Once the client enters the subscripted state it is not supposed to issue
any other commands, expect for additional `SUBSCRIBE`, `PSUBSCRIBE`,
`UNSUBSCRIBE` and `PUNSUBSCRIBE` commands.
