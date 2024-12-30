# An Epic Filesystem Quest 
==================================================================================================================================================================================================================================================================================================================================
it is too long code hostly speaking .so first we need to change to a directory and search for the hidden file by 'ls -a ' then we will find a file then read that file by using 'cat' then again it tells to go to new directory continutie like that ..at one point of time it tells to read th efile without going into to directory 
then use ls and the directory it mentioned  so u get the names of files it have then use cat and the directory and the file name  to get the result 
=============================================================================================================
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls
INFO  boot       dev  flag  lib    lib64   media  nix  proc  run   srv  tmp  var
bin   challenge  etc  home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~an-epic-filesystem-quest:/$ cat INFO
Congratulations, you found the clue!
The next clue is in: /usr/share/perl/5.30.0/unicore/lib/SD

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/$ cd  /usr/share/perl/5.30.0/unicore/lib/SD
hacker@commands~an-epic-filesystem-quest:/usr/share/perl/5.30.0/unicore/lib/SD$ ls -a
.  ..  .HINT  Y.pl
hacker@commands~an-epic-filesystem-quest:/usr/share/perl/5.30.0/unicore/lib/SD$ cat .HINT
Yahaha, you found me!
The next clue is in: /usr/share/icons/hicolor/16x16/emblems
hacker@commands~an-epic-filesystem-quest:/usr/share/perl/5.30.0/unicore/lib/SD$ cd  /usr/share/icons/hicolor/16x16/emblems
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/emblems$ ls -a
.  ..  README
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/emblems$ cat  README
Yahaha, you found me!
The next clue is in: /usr/share/doc/libmagic-mgc
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/emblems$ cd  /usr/share/doc/libmagic-mgc
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libmagic-mgc$ ls -a
.  ..  LEAD  README.Debian  changelog.Debian.gz  copyright
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libmagic-mgc$ cat  README.Debian

Between architectures, the compiled magic at /usr/lib/file/magic.mgc
differs only in the endianness. The libmagic library can auto-detect
wrong endianness and handle that situation gracefully, at a significant
performance cost though.

Therefore: If you run file/libmagic in a mixed-endianness multi-arch
setup, choose the architecture for libmagic-mgc wisely.
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libmagic-mgc$ cat  LEAD
Tubular find!
The next clue is in: /opt/aflplusplus/nyx_mode/libnyx/libnyx/target/release/.fingerprint/config-9071a9273268cefc
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libmagic-mgc$ cd /opt/aflplusplus/nyx_mode/libnyx/libnyx/target/release/.fingerprint/config-9071a9273268cefc
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/libnyx/libnyx/target/release/.fingerprint/config-9071a9273268cefc$ ls -a
.  ..  INSIGHT  dep-lib-config  invoked.timestamp  lib-config  lib-config.json
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/libnyx/libnyx/target/release/.fingerprint/config-9071a9273268cefc$ cat INSIGHT
Yahaha, you found me!
The next clue is in: /opt/pwndbg/.venv/lib/python3.8/site-packages/pip/_internal/models
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/libnyx/libnyx/target/release/.fingerprint/config-9071a9273268cefc$ cd  /opt/pwndbg/.venv/lib/python3.8/site-packages/pip/_internal/models
hacker@commands~an-epic-filesystem-quest:/opt/pwndbg/.venv/lib/python3.8/site-packages/pip/_internal/models$ ls -a
.      __init__.py   direct_url.py      installation_report.py  search_scope.py     wheel.py
..     __pycache__   format_control.py  link.py                 selection_prefs.py
TRACE  candidate.py  index.py           scheme.py               target_python.py
hacker@commands~an-epic-filesystem-quest:/opt/pwndbg/.venv/lib/python3.8/site-packages/pip/_internal/models$ cat      __pycache__
cat: __pycache__: Is a directory
hacker@commands~an-epic-filesystem-quest:/opt/pwndbg/.venv/lib/python3.8/site-packages/pip/_internal/models$ cat TRACE
Lucky listing!
The next clue is in: /opt/aflplusplus/nyx_mode/QEMU-Nyx/capstone_v4/msvc

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/opt/pwndbg/.venv/lib/python3.8/site-packages/pip/_internal/models$ cd  /opt/aflplusplus/nyx_mode/QEMU-Nyx/capstone_v4/msvc
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/capstone_v4/msvc$ ls
README        capstone_static            test_arm64            test_evm    test_mips      test_systemz     test_xcore
SNIPPET       capstone_static_winkernel  test_basic            test_iter   test_ppc       test_tms320c64x
capstone.sln  cstool                     test_customized_mnem  test_m680x  test_skipdata  test_winkernel
capstone_dll  test_arm                   test_detail           test_m68k   test_sparc     test_x86
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/capstone_v4/msvc$ cat SNIPPET
Lucky listing!
The next clue is in: /usr/share/javascript/mathjax/jax/output/SVG/fonts/STIX-Web/Alphabets/Regular

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/capstone_v4/msvc$ cd  /usr/share/javascript/mathjax/jax/output/SVG/fonts/STIX-Web/Alphabets/Regular
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/SVG/fonts/STIX-Web/Alphabets/Regular$
ls
GIST  Main.js
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/SVG/fonts/STIX-Web/Alphabets/Regular$
cat GIST
Great sleuthing!
The next clue is in: /usr/share/racket/pkgs/racket-doc/pkg/scribblings/compiled

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/SVG/fonts/STIX-Web/Alphabets/Regular$
ls -a  /usr/share/racket/pkgs/racket-doc/pkg/scribblings/compiled
.                           common_rkt.dep          envvars_scrbl.zo           lib_scrbl.dep   pkg_scrbl.zo
..                          common_rkt.zo           getting-started_scrbl.dep  lib_scrbl.zo    strip_scrbl.dep
POINTER-TRAPPED             db_scrbl.dep            getting-started_scrbl.zo   name_scrbl.dep  strip_scrbl.zo
apis_scrbl.dep              db_scrbl.zo             git-workflow_scrbl.dep     name_scrbl.zo
apis_scrbl.zo               dirs-catalog_scrbl.dep  git-workflow_scrbl.zo      path_scrbl.dep
catalog-protocol_scrbl.dep  dirs-catalog_scrbl.zo   implementation_scrbl.dep   path_scrbl.zo
catalog-protocol_scrbl.zo   envvars_scrbl.dep       implementation_scrbl.zo    pkg_scrbl.dep
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/SVG/fonts/STIX-Web/Alphabets/Regular$
cat /usr/share/racket/pkgs/racket-doc/pkg/scribblings/compiled/POINTER-TRAPPED
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{U7c-QMreqgaM2Cyd4N98uC5d8wd.dljM4QDL4cDO0czW}
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/SVG/fonts/STIX-Web/Alphabets/Regular$
=========================================================================================================
