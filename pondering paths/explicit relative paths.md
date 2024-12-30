# explicit relative paths
============================================================================
i have linked the terminal.then run the absolute path ...then run it to new directory and run relative path with explicit function
=================================================================
hacker@paths~explicit-relative-paths-from-:~$ /challenge/run
Incorrect...
You are not currently in the / directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~explicit-relative-paths-from-:~$ cd /
hacker@paths~explicit-relative-paths-from-:/$ challenge/run/./
ssh-entrypoint: challenge/run/./: Not a directory
hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{4gfjvRTlvdEBN9v4UBbIxJOjl7E.dBTN1QDL4cDO0czW}
================================================================================
