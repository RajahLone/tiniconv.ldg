# tiniconv.ldg

Library using the LDG system and the tiny charset convertion functions.

Please read the how-to and functions calls and test program.

# installation for makefiles

- pre-requisite: different targets of libtiniconv.a, libldg.a in /opt/cross-mint/m68k-atari-mint/lib/

- get [tiniconv_r2_src.zip](https://ptonthat.fr/files/tiniconv/tiniconv_r2_src.zip) and unpack the contents to ./

- install [libcmini/lib/](https://github.com/freemint/libcmini/releases/) a files on a location outside /opt/cross-mint/m68k-atari-mint/lib/ (ie in your workspace besides other projects) and fix $CMINI path in the Makefile.

- tiniconv.ldg.xcodeproj is for Xcode 26.3, you may not need it if you use something else.
