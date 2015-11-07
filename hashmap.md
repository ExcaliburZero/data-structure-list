# HashMap
HashMaps are a type of data structure which allows you to store objects or values so that you can access them by providing a correspoding value. Each entry in the data structure has a key, which is a value or an object, and through providing the key, the HashMap returns the corresponding stored value or object.

HashMap is a defualt class of Java, and can be used by importing it with the following import statement:
```Java
import java.util.HashMap
```

## Visual
| Key | Value |
|-----|-------|
|"city"|"Oswego"|
|"zipcode"|"12345"|
|"state"|"New York"|

Running `hashMapName.get("zipcode")` would return `"12345"`.

# Methods
| Method | Description |
|--------|-------------|
| `get(Object key)` | Gets the value or object stored with the given key. |
| `put(K key, V value)` | Stores the given value with the given key. |
| `remove(Object key)` | Removes the value stored with the specified key. |
| `size()` | Returns the number of entries in the HashMap. |

For more information on the HashMap class and its corresponding methods, see its [documentation](http://docs.oracle.com/javase/8/docs/api/java/util/HashMap.html).

