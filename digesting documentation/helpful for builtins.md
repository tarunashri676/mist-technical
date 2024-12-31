# helpful for bulitins 
==============================================================================
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "gK8QQTs9".
hacker@man~help-for-builtins:~$ challenge  --secret gK8QQTs9
Correct! Here is your flag!
pwn.college{gK8QQTs9TVYGT0ieycRq3349qWP.dRTM5QDL4cDO0czW}

=========================================================================
