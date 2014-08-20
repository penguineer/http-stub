http-stub
=========

A stub HTTP server.

Following reports of scans on all open TCP ports and the search for weak machines to be turned into "drones" by government agencies [1], this project aims at creating a stub HTTP server with the following features:
* The server constantly seems to be under a very high load. Processing requests takes a while.
* Eventually, all requests will result in 403.
* Optional: Access data (including authentication data) can be logged.
The stub server can be deployed on all machines with a publicly accessible HTTP port (80) to slow down the crawling.


Can we even collect and map the resulting data? Is there a pattern in access and intrusion attemps?


[1] http://www.heise.de/newsticker/meldung/NSA-GCHQ-Hacienda-Die-vollstaendige-Kolonisierung-des-Netzes-2292859.html
