# into to commands
Challenge Overview
In this level, the task was to invoke the hello command in the terminal to retrieve the flag.

Solution
I used the following command to solve the challenge:

hello

Flag
The flag I received was:

pwn.college{IICqR3fIEc58_RlF1WvP7WQme7r.ddjNyUDLxAjN0czW}

```bash
overfallranger@overfalls-MacBook-Air ~ % ssh -i ./key hacker@dojo.pwn.college


Connected!                                                                        

hacker@hello~intro-to-commands:~$ 
hacker@hello~intro-to-commands:~$ hello
Success! Here is your flag:
pwn.college{IICqR3fIEc58_RlF1WvP7WQme7r.ddjNyUDLxAjN0czW}
```