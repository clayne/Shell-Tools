Shell::Tools
============

This is the distribution of the Perl module
[`Shell::Tools`](https://metacpan.org/pod/Shell::Tools).

It is a Perl extension to reduce boilerplate in Perl shell scripts.

Please see the module's documentation (POD) for details
(try the command `perldoc lib/Shell/Tools.pm`)
and the file `Changes` for version information.

[![Travis CI Build Status](https://travis-ci.org/haukex/Shell-Tools.svg)](https://travis-ci.org/haukex/Shell-Tools)
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/haukex/Shell-Tools?svg=true)](https://ci.appveyor.com/project/haukex/shell-tools)
[![Kwalitee Score](https://cpants.cpanauthors.org/dist/Shell-Tools.svg)](https://cpants.cpanauthors.org/dist/Shell-Tools)
[![CPAN Testers](https://haukex.github.io/my-badges/Shell-Tools.svg)](http://matrix.cpantesters.org/?dist=Shell-Tools)

Installation
------------

To install this module type the following:

	perl Makefile.PL
	make
	make test
	make install

If you are running Windows, you may need to use `dmake`, `nmake`,
or `gmake` instead of `make`.

Dependencies
------------

Requirements: Perl v5.8 or higher (a more current version is strongly
recommended) and several of its core modules; users of Perl before v5.10
may need to upgrade a few core modules. There are several additional
recommended modules that can be installed from CPAN. The full list of
modules and their versions can be found in the file `Makefile.PL`.
This module should work on any platform supported by these modules.

Author, Copyright and License
-----------------------------

Copyright (c) 2014 Hauke Daempfling <haukex@zero-g.net>.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl 5 itself.

For more information see the Perl Artistic License,
which should have been distributed with your copy of Perl.
Try the command `perldoc perlartistic` or see
<http://perldoc.perl.org/perlartistic.html>

