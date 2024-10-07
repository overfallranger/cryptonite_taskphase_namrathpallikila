I navigated to the /challenge directory:
cd /challenge

I then executed the program using the explicit relative path:
./run

Flag
The flag I received was:
pwn.college{A5qLOlcDlL2574NmDWIvY7u7FyC.dFTN1QDLxAjN0czW}
```bash
hacker@paths~implicit-relative-path:~$ cd /challenge
hacker@paths~implicit-relative-path:/challenge$ pwd
/challenge
hacker@paths~implicit-relative-path:/challenge$ ./run
Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{A5qLOlcDlL2574NmDWIvY7u7FyC.dFTN1QDLxAjN0czW}
```