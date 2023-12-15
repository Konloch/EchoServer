# [Echo Server](https://github.com/Konloch/EchoServer/tree/main/Echo-Server)
[Echo Server](https://github.com/Konloch/EchoServer/tree/main/Echo-Server) is a low-level non-blocking [RFC-862](https://www.rfc-editor.org/rfc/rfc862) compliant echo server.

# [CR Echo Server](https://github.com/Konloch/EchoServer/tree/main/CR-Echo-Server)
[CR Echo Server](https://github.com/Konloch/EchoServer/tree/main/CR-Echo-Server) is a low-level non-blocking echo server.

It will echo-back the contents of the buffer if it has reached 1024 characters, or encountered a carriage return.

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

## Links
* [Website](https://konloch.com/EchoServer/)
* [Discord Server](https://discord.gg/aexsYpfMEf)
* [Download Releases](https://github.com/Konloch/EchoServer/releases)
