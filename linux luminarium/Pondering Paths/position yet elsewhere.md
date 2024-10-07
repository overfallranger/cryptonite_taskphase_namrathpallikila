I started by SSH-ing into the pwn.college server.
After successfully logging in, I navigated to the /sys/kernel directory using the following command:
cd /sys/kernel
Once I was in the correct directory, I executed the program using its absolute path:
/challenge/run
The program ran successfully, and I was able to capture the flag.
Flag
The flag I received was:
pwn.college{kbSmU0z7WT1X-VL25ZeZ1liDtSZ.dhDN1QDLxAjN0czW}
```bash
hacker@paths~position-yet-elsewhere:~$ cd /sys/kernel
hacker@paths~position-yet-elsewhere:/sys/kernel$ pwd
/sys/kernel
hacker@paths~position-yet-elsewhere:/sys/kernel$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{kbSmU0z7WT1X-VL25ZeZ1liDtSZ.dhDN1QDLxAjN0czW}
```