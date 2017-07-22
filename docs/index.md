## Introduction

upnpmap is a simple set of command line tools used for querying and manipulating UPnP servers.

If you're creating your own devices or services which need access through your home firewall, UPnP is a more 
automated alternative to the hassle of manual port forwarding. But the problem is that usually it takes a 
development library to map UPnP ports.

There are some command line tools available, but finding one with just the right set of features and flexibility 
was proving quite difficult. Out of this need rose upnpmap, a dead-simple set of command line scripts written in Python 
which take all of the development effort out of mapping UPnP ports.

You can easily check and map ports in a cron job or other shell script using upnpmap.
