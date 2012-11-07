====================
Ivy P4
====================

Forked from Felix Drueke's ivyp4:
- Fixed some path handling bugs in P4Resolver
- Fixed listing of "deleted" files
- Upgraded to p4java p4java-2012.3.526908 
- Use gradle 1.2 to build (tests not ported yet).

From original README:

IvyP4 implements a resolver for `Ivy <http://ant.apache.org/ivy/>` for that allows
you to use the SCM system `Perforce <http://www.perforce.com/>` as a repository for
artifacts.

IvyP4 lets you define a place on your perforce server as your repository for Ivy artifacts.
Ivy will then work with this repository like with any other type of repository (e.g. filesystems,
ftp servers, etc.).

This project was inspired by the excellent `Subversion resolver for Ivy <http://code.google.com/p/ivysvn/>`.
