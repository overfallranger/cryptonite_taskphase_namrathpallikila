Challenge Overview
In this challenge, I needed to retrieve the flag from the /usr/aarch64-linux-gnu/include/flag directory using the cat command with an absolute path. I was not allowed to change directories using cd, so I had to retrieve the flag directly from its absolute location.

Solution

I used the following command to retrieve the flag:
cat /usr/aarch64-linux-gnu/include/flag
Flag
The flag I received was:
pwn.college{Q2Gq-x9_D_dFk-yJCeNa9T5ixdV.dBjM5QDLxAjN0czW}

```bash
You cannot use the 'cd' command in this level, and must retrieve the flag by 
absolute path. Plus, I hid the flag in a different directory! You can find it 
in the file /usr/aarch64-linux-gnu/include/flag. Go cat it out **without** 
cding into that directory!
hacker@commands~more-catting-practice:~$ cat /usr/aarch64-linux-gnu/include/flag
pwn.college{Q2Gq-x9_D_dFk-yJCeNa9T5ixdV.dBjM5QDLxAjN0czW}
```