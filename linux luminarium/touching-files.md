Challenge Overview
In this challenge, I needed to create two files (/tmp/pwn and /tmp/college) and then run the /challenge/run program to retrieve the flag.

Solution

I navigated to the /tmp directory using:
cd /tmp

I created the files using the following commands:
touch pwn
touch college

I confirmed the files were created with:
ls
Output:
bin college hsperfdata_root pwn tmp.G9qthVCks5

I then ran the program using:
/challenge/run

Flag
The flag I received was:
pwn.college{UxKxmobvCoTJKR5ORTKmAlfnE-F.dBzM4QDLxAjN0czW}
```bash
hacker@commands~touching-files:~$ cd /tmp
hacker@commands~touching-files:/tmp$ pwd
/tmp
hacker@commands~touching-files:/tmp$ touch pwn
hacker@commands~touching-files:/tmp$ touch college
hacker@commands~touching-files:/tmp$ ls
bin  college  hsperfdata_root  pwn  tmp.G9qthVCks5
hacker@commands~touching-files:/tmp$ /challenge/run
Success! Here is your flag:
pwn.college{UxKxmobvCoTJKR5ORTKmAlfnE-F.dBzM4QDLxAjN0czW}
```