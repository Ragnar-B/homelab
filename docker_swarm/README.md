# Docker Swarm

These compose files were used in a Docker Swarm setup. The setup were 3 Raspberry PI's with a 4th which was used as a NAS.

The NAS had a NFS share which all the hosts mounted through the Docker-Compose files. That way the data could be shared between hosts. 

When a host fails the service would be restored on another host.
