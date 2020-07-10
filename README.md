# ConcurrentSoftHashMap
Implementation of ConcurrentSoftHashMap. 

This is thread-safe Soft reference HashMap.

exmaple of Usage:

```
import cz.b2b.jcl.util.ConcurrentSoftHashMap;

...

//The number of "hard" references to hold internally.
int hardSize = 100;
private Map<String, Object> CACHE = new ConcurrentSoftHashMap<>(hardSize);
CACHE.put("first", new ArrayList());
```
