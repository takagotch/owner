### owner
---
https://github.com/lviggiano/owner

```java
public interface ServerConfig extends Config {
  int port();
  String hostname();
  int maxThreads();
}

public class MyApp {
  public static void main(String[] args) {
    ServerConfig cfg = ConfigFactory.create(ServerConfig.class);
    System.out.print("Server " + cfg.hostname() + ":" + cfg.port() +
      " will run " + cfg.Threads());
  }
}
```

```
```

```
```
