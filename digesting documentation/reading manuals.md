# reading manuals 
========================================================================
first reads out the manual of that whole directory.then it gives us what to do in the manual to get the flag.
=============================================================================================================
hacker@man~reading-manuals:~$ man challenge

CHALLENGE(1)                                                   Challenge Commands                                                   CHALLENGE(1)

NAME
       /challenge/challenge - print the flag!

SYNOPSIS
       challenge OPTION

DESCRIPTION
       Output the flag when called with the right arguments.

       --fortune
              read a fortune

       --version
              output version information and exit

       --ovqbnb NUM
              print the flag if NUM is 904

AUTHOR
       Written by Zardus.

REPORTING BUGS
       The repository for this dojo: <https://github.com/pwncollege/linux-luminarium/>

SEE ALSO
       man(1) bash-builtins(7)

pwn.college                                                         May 2024                                                        CHALLENGE(1)
hacker@man~reading-manuals:~$ /challenge/challenge  --ovqbnb 904
Correct usage! Your flag: pwn.college{oBvRIqE9YbN_Lnbv0KINjxWWJWZ.dRTM4QDL4cDO0czW}

=================================================================================================================================
