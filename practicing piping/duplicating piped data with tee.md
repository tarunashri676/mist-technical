# duplicating piped data with tee 
***
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | tee /challenge/run_ouput | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ cat /challenge/run_output
cat: /challenge/run_output: No such file or directory
hacker@piping~duplicating-piped-data-with-tee:~$ cat /challenge/run_ouput
Usage: /challenge/pwn --secret [SECRET_ARG]

SECRET_ARG should be "AFxh_Rsj"
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --AFxh_Rsj | tee /challenge/run_ouput | /challenge/college
Processing...
WARNING: you are overwriting file /challenge/run_ouput with tee's output...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | tee /challenge/run_ouput | /challenge/college --AFxh_Rsj
Processing...
WARNING: you are overwriting file /challenge/run_ouput with tee's output...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret [AFxh_Rsj] | tee /challenge/run_ouput | /chellenge/college
ssh-entrypoint: /chellenge/college: No such file or directory
Processing...
You must pipe the output of /challenge/pwn into /challenge/college (or 'tee'
for debugging).
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret [AFxh_Rsj] | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge.pwn -- secret [AFxh_Rsj] | tee /challenge/run_ouput | /challenge/college
ssh-entrypoint: /challenge.pwn: No such file or directory
WARNING: you are overwriting file /challenge/run_ouput with tee's output...
/challenge/secret needs to the on the receiving end of the output of
'/challenge/pwn' (or 'tee' for debugging).
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret AFxh_Rsj | tee /challenge/run_ouput | /challenge/college
Processing...
WARNING: you are overwriting file /challenge/run_ouput with tee's output...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{AFxh_Rsj4_eyZtVL_93-UF8iE8N.dFjM5QDL4cDO0czW}
***
