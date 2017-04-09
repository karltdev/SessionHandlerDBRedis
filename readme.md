Session Handler DB Redis
========================
This is a Processwire module rewritten from a Processwire core module - SessionHandlerDB. This module also adds "session" under Setting as the same way as SessionHandlerDB to check the active sessions. This project borrowed some code from netcarver/PW-SessionHandlerRedis.

Prerequsite:
1. Installed Redis on local.
2. Installed phpredis on local.

How to use:
1. Install the module as other modules.
2. Configure the module as your needs like the host of Redis server and the prefix for the session.
3. If it is unable to connect to the defined host, it will fall back to local Redis server.