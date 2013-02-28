#####################
Backup with PostreSQL
#####################

:Speaker:
    Joshua Drake

:Date:
    2013-02-22

:Site:
    http://launchpad.net/hockeypuck

Summary
=======

+ http://www.postgresql.org/docs/9.2/interactive/backup.html is the
  current backup documentation.

+ PostgreSQL now supports streaming backup, which I haven't used, but
  appears to be easier to set up than MySQL, for instance - you can set
  up a replica of an existing server from a new backup server without
  needing to stop the primary server.  The new tool is 'pg_basebackup'.
  This can be chained, and combined with PITR (Point in time recovery).

+ Joshua showed a small script to do a dump of each database from a
  cluster separately, this had some advantages over dumping the entire
  database.

I will probably set up a simple instance of PostgreSQL with streaming
replication, this is something I have been meaning to do for a while.

