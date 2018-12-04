# nginx-proxy

This is an example showing how different http servers can be easily unified. The servers are assumed to operate in a docker container each. They are unified by a reverse proxy, of course also operating in a container.

The example shows a couple of example target servers and https termination in the reverse proxy.

It's based on the excellent https://github.com/jwilder/nginx-proxy
