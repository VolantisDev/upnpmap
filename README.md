# upnpmap
A simple set of scripts to manage upnp mappings for use in configuration management scripts.

Adapted from a set of scripts created by Silas S. Brown [here](http://people.ds.cam.ac.uk/ssb22/setup/upnp.html).

## Commands

### upnpmap-add [port] [internal-port]

Add a simple port forwarding rule. The first argument should be the port to forward. Optionally, the second argument can be the local port to use.

### upnpmap-date

Simply shows the current date and time from the upnp server.

### upnpmap-delete [port]

Deletes a port forwarding rule. Provide the external port as the first argument.

### upnpmap-ip

Show the current external IP address.

### upnpmap-list

Shows a table of current port forwarding rules.
