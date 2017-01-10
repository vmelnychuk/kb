### Alternative Optional implementation
Opetional implementation
```java
package boots;

public class Optional<T> {
    public final boolean exist;
    T cargo;
}

Optional<String> name;

// some logic

if (op.exist) {
        // do some logic if cargo is not null;
}

```
