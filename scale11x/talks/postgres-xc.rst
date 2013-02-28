#####################
Backup with PostreSQL
#####################

:Speaker:
    Jim Mlodgenski

:Date:
    2013-02-22

:Site:
    http://postgresxc.wikia.com/wiki/Postgres-XC_Wiki

Summary
=======

Postgres-XC is a clustering technology for Postgres that allows a
large high-performance cluster to be built using Postgres instances.
An intermediate query writer does sharding, and also combines results
from multiple shards- standard SQL can be used.  The resultant system
scales at roughly .6 per system added (i.e. 8 boxes will run roughly
5x faster than 1 box).

The system is not designed for high reliability, although individual
nodes can be set up HA.

There seemed to be some interest in merging this with the main
Postgres project.
