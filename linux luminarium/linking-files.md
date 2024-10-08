In this challenge, I needed to create a symbolic link that pointed to the /flag file, then use it to retrieve the flag through the /challenge/catflag command.

Solution

I created a symbolic link using:
ln -s /flag /home/hacker/not-the-flag

I verified the symbolic link with:
file /home/hacker/not-the-flag
Output:
/home/hacker/not-the-flag: symbolic link to /flag

I ran the command to retrieve the flag using the symbolic link:
/challenge/catflag

Flag
The flag I received was:
pwn.college{owwKplz-15qiWAH82aK_OsJukMT.dlTM1UDLxAjN0czW}

```bash
hacker@commands~linking-files:~$ ln -s /flag /home/hacker/not-the-flag
hacker@commands~linking-files:~$ file /home/hacker/not-the-flag
/home/hacker/not-the-flag: symbolic link to /flag
hacker@commands~linking-files:~$ /challenge/catflag
About to read out the /home/hacker/not-the-flag file!
pwn.college{owwKplz-15qiWAH82aK_OsJukMT.dlTM1UDLxAjN0czW}
```