# LRU CACHE:

Write the code to implement a “Least-Recently Used” (LRU) Cache.

A correctly constructed LRU Cache will have its maximum capacity set at the time of construction,
and when adding new keys that cause the capacity to be exceeded, the “least recently used” item
needs to be identified and discarded.

```
let lruCache = new LRUCache({
   size: <integer number of max items>
});

lruCache.put(key, value)
lruCache.get(key) -> value
lruCache.del(key)
lruCache.reset()
```

Key Requirements:
1. You must initialize a cache with a maximum size
2. You must be able to put the value of a key.
3. You must be able to get the value of a key.
Note : Both, reading and writing the value of a key are considered a use of that key.
4. You must be able to delete a key. Attempting to delete a key that doesn't exist is a no-op.
5. You must be able to reset the cache, which will remove all items from the cache.


Evaluation:
Your submission will be evaluated based on the following criteria.
1. How well the application captures the functionality described in the requirements, in terms of answer correctness and interface.
2. The data types used in the solution.
3. The clarity, readability and organization of the code.
4. Documentation around the process to setup and run the code

Submission:
To submit your solution, please let your recruiter know, and give karthik@forumvc.com access to your private repo so that we can review and run it.
