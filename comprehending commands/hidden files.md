# hidden files 
=================================================================================
i have linked the terminal and then changed the directory to find the file there ..for finding the hidden file i used 'ls -a' and then found the hidden file ...to read out the file i have used cat .
================================================================================================
hacker@commands~hidden-files:~$ cd /
hacker@commands~hidden-files:/$ ls -a
.   .dockerenv            bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-99072780211742  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ cat .flag-99072780211742
pwn.college{oGyqGqAWFwR8JJz8nmah-wvHI-b.dBTN4QDL4cDO0czW}
====================================================================================
