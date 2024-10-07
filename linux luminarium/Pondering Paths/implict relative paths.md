I started by navigating to the root directory:
cd /
I then executed the run program using the relative path:
./challenge/run
Flag
The flag I received was:
pwn.college{AM0BH3kUbLzHjrs2SwrM5MaDq0S.dlDN1QDLxAjN0czW}
```bash
hacker@paths~implicit-relative-paths-from-:/$ cd /
hacker@paths~implicit-relative-paths-from-:/$ pwd
/
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{AM0BH3kUbLzHjrs2SwrM5MaDq0S.dlDN1QDLxAjN0czW}
```