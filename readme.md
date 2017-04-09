# Session Handler DB Redis

This is a Processwire module using Redis as session handler. This is rewritten from a Processwire core module - SessionHandlerDB and borrowed some code from netcarver/PW-SessionHandlerRedis. This module also adds "session" under Setting as the same way as SessionHandlerDB to check the active sessions.

## Prerequsite
1. Installed Redis on local.
2. Installed phpredis on local.

## How to use
1. Install the module.
2. Configure the module as your needs like the host of Redis server and the prefix for the session.
3. If it is unable to connect to the defined host, it will fall back to local Redis server.

## License
MIT