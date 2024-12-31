# exporting variables
***
hacker@variables~exporting-variables:~$ PWN=COLLEGE
You've set the PWN variable to the proper value!
hacker@variables~exporting-variables:~$ COLLEGE="/challenge/run"
You've set the PWN variable to the proper value!
You've set the COLLEGE variable, but it does not look like the value is
correct. Make sure that the value is PWN!
hacker@variables~exporting-variables:~$ export pwn
You've set the PWN variable to the proper value!
You've set the COLLEGE variable, but it does not look like the value is
correct. Make sure that the value is PWN!
hacker@variables~exporting-variables:~$ export PWN
You've set the PWN variable to the proper value!
You've set the COLLEGE variable, but it does not look like the value is
correct. Make sure that the value is PWN!
hacker@variables~exporting-variables:~$ COLLEGE=PWN
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!
hacker@variables~exporting-variables:~$ export PWN
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!
hacker@variables~exporting-variables:~$ sh
sh-5.2$ /challenge/run
CORRECT!
You have exported PWN=COLLEGE and set, but not exported, COLLEGE=PWN. Great
job! Here is your flag:
pwn.college{Ao3qj2KenHefjpukrMNffPMX39p.dJjN1QDL4cDO0czW}
***

