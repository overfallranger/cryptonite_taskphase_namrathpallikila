I created a file named a inside my home directory using the command:
touch a

I ran the program with the following command:
/challenge/run ~/a

I used cat ~/a to read the flag from the file.

Flag
The flag I received was:
pwn.college{A8Mecpaunf2IaDePYhb5nOE2976.dNzM4QDLxAjN0czW}

```basah
hacker@paths~home-sweet-home:~$ touch a
hacker@paths~home-sweet-home:~$ /challenge/run ~/a
Writing the file to /home/hacker/a!
... and reading it back to you:
pwn.college{A8Mecpaunf2IaDePYhb5nOE2976.dNzM4QDLxAjN0czW}
hacker@paths~home-sweet-home:~$ cat ~/a
pwn.college{A8Mecpaunf2IaDePYhb5nOE2976.dNzM4QDLxAjN0czW}
```