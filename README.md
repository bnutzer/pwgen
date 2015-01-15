pwgen is a password generator; see
http://sourceforge.net/projects/pwgen/

This version includes a patch that exists in various Linux distributions; I
took it from OpenSUSE's source package.

Additionally, it creates a shared library libpwgen.so from the source; this
library, altough flawed (it is not thread safe due to global variables),
provides an interface to be used by my Crypt::PwGen Perl module (to be found
at github as well).

(c) Theodore Ts'o <tytso@alum.mit.edu>,
    Bastian Friedrich <bastian@bastian-friedrich.de>
