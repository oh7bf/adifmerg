
adifmerg
========

Small utility to convert ADIF files. To produce output without USERDEF fields
use the switch __-u__. See the manual page in doc/.

qsorep
------

Create and maintain ADIF-file repository. See the manual page in doc/.

Install
-------

See the __install__ script. For easier command line editing one of the 
following could be installed on Rasbian Wheezy

```shell
libterm-readline-gnu-perl  or 
libterm-readline-perl-perl  or 
libterm-readline-zoid-perl
```

Files
-----

```asciidoc
adifmerg 		- main program 
CHANGELOG   		- history of changes
COPYING  		- GPL2
doc			- manual page
qsorep                  - qso repository script
README    		- this file
script/contest		- contest scripts
script/eqslcc		- eQSLcc scripts
script/log              - logging scripts
script/lotw		- LoTW scripts
script/util		- utility scripts
test/runtest		- test routine 
testrep/                - test repository for qsorep
```

Testing
--------

Test first by __cd test__ and __./runtest__.

