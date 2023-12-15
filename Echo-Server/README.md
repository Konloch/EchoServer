# Echo Server
Echo Server is a low-level non-blocking [RFC-862](https://www.rfc-editor.org/rfc/rfc862) compliant echo server.

## Links
* [Website](https://konloch.com/EchoServer/)
* [Discord Server](https://discord.gg/aexsYpfMEf)
* [Download Releases](https://github.com/Konloch/EchoServer/releases)

## How To Use
You can run the Java Jar file directly, or you can use it as a library
```java
EchoServer server = new EchoServer(7, 1);
server.start();
```

### How To Connect
Using `telnet` you can easily test the server.
```
telnet localhost 7
```
