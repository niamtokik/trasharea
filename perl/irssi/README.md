This script save all link on IRC (with Irssi) into SQLite database.

You need:

* perl DBI
* perl DBD::SQLite
* sqlite3
* Irssi

This script was tested on CentOS6.4 with :

* perl-5.10.1-131.el6_4.x86_64
* perl-DBI-1.609-4.el6.x86_64
* perl-DBD-SQLite-1.27-3.el6.x86_64
* sqlite-3.6.20-1.el6.x86_64
* irssi-0.8.15-5.el6.x86_64

This script was tested on FreeBSD 9.1 with:

* perl-5.14.2_3
* p5-DBI-1.623
* sqlite3-3.7.17_1
* irssi-0.8.15_5

2014-07-14: rewriting function and add automatic sqlite purge + debug mode.

2013-09-03: v0.2 just works. Need some improvement, but works. :)

2013-09-03: Script is in "Alpha Mode". I test sql schema and this
	    script is not fully functionnal... v0.1 (first shot) is
	    ready to work.

By default all data are saved into ~/.irssi/. 

