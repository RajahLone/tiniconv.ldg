# tiniconv.ldg

Library using the LDG system and the tiny charset convertion functions.

Please read the how-to and functions calls and test program.

# installation for makefiles

- pre-requisite: different targets of libtiniconv.a, libldg.a in /opt/cross-mint/m68k-atari-mint/lib/

- in an empty folder,  
   ```mkdir ./build/68000```  
   ```mkdir ./build/68020```  
   ```mkdir ./build/ColfFire```  

- get [tiniconv_r1_src.zip](https://ptonthat.fr/files/tiniconv/tiniconv_r1_src.zip) and unpack the contents of /tiniconv.ldg/ to
   ```./README.md  
   ./Makefile  
   ./main.c  
   ./tiniconv.ldg.xcodeproj```  

- tiniconv.ldg.xcodeproj is for Xcode 16.0, you may not need it if you use something else.
