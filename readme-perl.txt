To build the Perl code:
 - install the swig package
   on Debian this is valled "swig"

 - run:
	make cleware_perl
   this will produce: cleware.so and cleware.pm
   These two files must be installed in your Perl system.

 - look at example.pl to see how it works (e.g. execute perl example.pl)
   make sure that the user you run your scripts with has enough rights to access the USB devices!
