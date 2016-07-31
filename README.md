comm-net
========

##2016-07-31
So what I would like to achieve here (haven't started yet, no code exists) is a peer to peer communication client.
* I'd like to build an android GUI for it
* I think I'll also need a CLI proxy/client, which should be able to run on OpenWRT devices
 * to relieve the battery-powered android phones from having to always listen for incoming connections (staying awake)
 * at least where I come from (Austria) most mobile network providers won't give phones public reachable IP-adresses, only NATed access.
* Clients (GUI and or CLI) for Windows and MAC would be a nice to have, maybe once Android GUI + OpenWRT CLI Proxy are done.

###OpenWRT because:
* many people have a OpenWRT capable wifi router at home anyway.
* many of which even have USB-ports which allow attaching storage devices, for example to also being able to relay bigger messages like multimedia.
* when it is able to run on OpenWRT, it will most certainly also run on any other linux machine, like NAS devices or Raspberry PIs.

Although I'm not really a fan, the only programming language I know is capable of running on OpenWRT is C++. I'm planning to do more research before starting to code though.
