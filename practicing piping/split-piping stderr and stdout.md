# split-piping stderr and stdout
***
hacker@piping~split-piping-stderr-and-stdout:~$ /challenge/hack >>(/challenge/planet) 2>(/challenge/the)
ssh-entrypoint: syntax error near unexpected token `('
hacker@piping~split-piping-stderr-and-stdout:~$ /challenge/hack > >(/challenge/planet) 2>(/challenge/the)
You must redirect my standard error into '/challenge/the'!
Are you sure you're properly redirecting /challenge/hack's standard error into
'/challenge/the'?
hacker@piping~split-piping-stderr-and-stdout:~$ /challenge/hack > >(/challenge/planet) 2>(/challenge/the)
You must redirect my standard error into '/challenge/the'!
Are you sure you're properly redirecting /challenge/hack's standard error into
'/challenge/the'?
hacker@piping~split-piping-stderr-and-stdout:~$ /challenge/hack > >(/challenge/planet) 2> >(/challenge/the)
Congratulations, you have learned a redirection technique that even experts
struggle with! Here is your flag:
pwn.college{ks_ZuPNAWNxn3j9JNMaf2GQy7ru.dFDNwYDL4cDO0czW}
***
