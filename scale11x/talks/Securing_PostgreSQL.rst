========================================
Securing PostgreSQL From External Attack
========================================

:Presenter:
 Bruce Momjian

:Date:
 2013-02-23

Summary
=======

Discussion of securing PostgreSQL from external attack.  Talk mainly
paralleled the documentation and was not super deep.  Basically, use
SSL, ideally client certificates, and don't use cleartext passwords in
the DB.  Some discussion of using GSSAPI and Kerberos after the
presentation.
