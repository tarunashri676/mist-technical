# redirecting input 
***
hacker@piping~redirecting-input:~$ college > PWN
ssh-entrypoint: college: command not found
hacker@piping~redirecting-input:~$ COLLEGE > PWN
ssh-entrypoint: COLLEGE: command not found
hacker@piping~redirecting-input:~$ echo COLLEGE > PWN
hacker@piping~redirecting-input:~$ /challenge/run < PWN
Reading from standard input...
Correct! You have redirected the PWN file into my standard input, and I read
the value 'COLLEGE' out of it!
Here is your flag:
pwn.college{0xptW6QT7TwoXnaTKgwt7IEdYgS.dBzN1QDL4cDO0czW}
***
