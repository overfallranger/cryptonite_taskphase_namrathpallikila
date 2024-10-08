Challenge Overview
In this challenge, I needed to create a directory /tmp/pwn and place a file named college inside it. Then, I was to run the /challenge/run program to verify my solution and retrieve the flag.

Solution

I navigated to the /tmp directory using:
cd /tmp

I created the directory using:
mkdir pwn

I navigated to the pwn directory using:
cd /tmp/pwn

I created the college file using:
touch college

I ran the program to verify the solution:
/challenge/run

Flag
The flag I received was:
pwn.college{US4PQw3epe31JqXTb_dLUAUrR7s.dFzM4QDLxAjN0czW}
```bash
hacker@commands~making-directories:~$ cd /tmp
hacker@commands~making-directories:/tmp$ pwd
/tmp
hacker@commands~making-directories:/tmp$ mkdir pwn
hacker@commands~making-directories:/tmp$ ls /tmp
bin  hsperfdata_root  pwn  tmp.G9qthVCks5
hacker@commands~making-directories:/tmp$ cd /tmp/pwn
hacker@commands~making-directories:/tmp/pwn$ touch college
hacker@commands~making-directories:/tmp/pwn$ ls /tmp/pwn
college
hacker@commands~making-directories:/tmp/pwn$ /challenge/run
Success! Here is your flag:
pwn.college{US4PQw3epe31JqXTb_dLUAUrR7s.dFzM4QDLxAjN0czW}
```