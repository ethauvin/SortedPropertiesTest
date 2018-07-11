To test:

```bash
./gradlew runPlugin run
```
then:

```bash
groovy src/main/groovy/com/example/App.groovy
```

No longer works in newer version of Java (> 8).

The `keys()` method in `java.util.Properties` is no longer called on `store()`.