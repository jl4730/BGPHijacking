# BGPHijacking

This is upgraded version of the [BGP Path Hijacking Attack Demo](https://github.com/mininet/mininet/wiki/BGP-Path-Hijacking-Attack-Demo)

## bgp.py
main file, defines the topology

## run.py
runs the simulation

## start_rogue.sh
starts rogue AS, begins the BGP hijacking

## stop_rogue.sh
stops rogue AS, stops the BGP hijacking

## webserver.py
initiates the simulation

## bgpd-R(X).conf
BGP configuration files for each of the routers

## zebra-R(X).conf
zebra is an IP routing manager. It provides kernel routing table updates, interface lookups, and redistribution of routes bwtween different routing protocols
