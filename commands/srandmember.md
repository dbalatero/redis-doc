

_Time complexity O(1)_

Return a random element from a Set, without removing the element.
If the Set is empty or the key does not exist, a nil object is returned.

The [SPOP][1] command does a similar work but the returned elemen
is popped (removed) from the Set.

## Return value

[Bulk reply][2]



[1]: /p/redis/wiki/SpopCommand
[2]: /p/redis/wiki/ReplyTypes