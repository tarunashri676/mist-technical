# grepping live output
***
hacker@piping~grepping-live-output:~$ /challenge/run | grep flag
[INFO] WELCOME! This challenge makes the following asks of you:
[INFO] - the challenge checks for a specific process at the other end of stdout : grep
[INFO] - the challenge will output a reward file if all the tests pass : /challenge/.data.txt

[HYPE] ONWARDS TO GREATNESS!

[INFO] This challenge will perform a bunch of checks.
[INFO] If you pass these checks, you will receive the /challenge/.data.txt file.

[TEST] You should have redirected my stdout to another process. Checking...
[TEST] Performing checks on that process!

[INFO] The process' executable is /nix/store/xpq4yhadyhazkcsggmqd7rsgvxb3kjy4-gnugrep-3.11/bin/grep.
[INFO] This might be different than expected because of symbolic links (for example, from /usr/bin/python to /usr/bin/python3 to /usr/bin/python3.8).
[INFO] To pass the checks, the executable must be grep.

[PASS] You have passed the checks on the process on the other end of my stdout!
[PASS] Success! You have satisfied all execution requirements.
[FLAG] Here is your flag:
flagging
flagged
camouflages
conflagration's
flag's
flagstaff's
flagship's
flagons
flagrant
camouflage's
flagstones
flagon
camouflaging
flagpoles
flagstaffs
flagstone
flagellates
flagellum
flagpole's
persiflage
flagships
conflagration
camouflaged
flagon's
flagellation
flagellated
flag
flagellation's
flagship
unflagging
flagellate
flagstaff
flags
flagella
camouflage
flagellating
conflagrations
flagellums
flagpole
flagrantly
flagstone's
flagellum's
persiflage's
hacker@piping~grepping-live-output:~$ grep flag /challenge/run
$DIR/chio.py --check_stdout_pipe grep --reward /challenge/.data.txt --chio_flag_fd 1
hacker@piping~grepping-live-output:~$ grep pwn.college /challenge/run
#!/opt/pwn.college/bash
hacker@piping~grepping-live-output:~$ /challenge/run | grep pwn.college
[INFO] WELCOME! This challenge makes the following asks of you:
[INFO] - the challenge checks for a specific process at the other end of stdout : grep
[INFO] - the challenge will output a reward file if all the tests pass : /challenge/.data.txt

[HYPE] ONWARDS TO GREATNESS!

[INFO] This challenge will perform a bunch of checks.
[INFO] If you pass these checks, you will receive the /challenge/.data.txt file.

[TEST] You should have redirected my stdout to another process. Checking...
[TEST] Performing checks on that process!

[INFO] The process' executable is /nix/store/xpq4yhadyhazkcsggmqd7rsgvxb3kjy4-gnugrep-3.11/bin/grep.
[INFO] This might be different than expected because of symbolic links (for example, from /usr/bin/python to /usr/bin/python3 to /usr/bin/python3.8).
[INFO] To pass the checks, the executable must be grep.

[PASS] You have passed the checks on the process on the other end of my stdout!
[PASS] Success! You have satisfied all execution requirements.
pwn.college{QMKIVUMCFSkYVGLyzL1nBUqMKB5.dlTM4QDL4cDO0czW}
***
