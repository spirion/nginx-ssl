Docker build for an instance of nginx incorporating SSL.

Reverse proxy used to provide an SSL entry point for a number of servers that do not implement SSL themselves.  The intention is to handle routing by linking domain names to specific ports exposed by Docker containers on the same host.
