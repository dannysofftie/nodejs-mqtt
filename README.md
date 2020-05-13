# Secure MQTT broker in Node.js.
Secure MQTT broker, uses certificate and/or username-password authentication.

Has support for connections over TCP sockets and WebSockets. TCP based connections are primarily for certificate based authentication which offers a pretty solid way to secure your broker from the public. WebSockets are for username-password based authentication, which is great for use with mqtt browser clients.

This project will demonstrate how to secure your broker from client connections, down to topic level filtering, to allow/deny clients to publish/subscribe to predefined topics. This is an added layer of security to your broker. 

## Dependencies
1. Aedes barebone MQTT broker - https://github.com/moscajs/aedes
2. Aedes redis persistence - https://github.com/moscajs/aedes-persistence-redis
3. 
