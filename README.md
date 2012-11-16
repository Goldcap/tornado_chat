Constellation.tv Tornado Chat
============
Python Tornado Chat Implementation with Redis/MongoDB

Synopsis
=============
This chat engine was used to serve 20,000 simultaneous users via asynchronous distributed python services.

Each service was run on multiple ports per server instance, and connected to a Redis server used to manage temporary data.

Each chat instance was run on a separate port (to simulate multithreaded responses), and proxied behind HA Proxy, eventually migrated to NGINX.

Caveats
=============
Please note that this is only a collection of sample code, and requires both MARKUP and server instances to work properly. For a working example, please contact the author.