Challenge Overview
In this challenge, I needed to search through a large file (/challenge/data.txt) containing a hundred thousand lines of text using the grep command to find the flag. The flag starts with pwn.college.

Solution

I used the following command to search for the flag:
grep "pwn.college" /challenge/data.txt

This command searched through the file and printed the line containing the flag.

Flag
The flag I received was:
pwn.college{E06LP6wkGa9eav21W5K3u_WSarl.ddTM4QDLxAjN0czW}

```bash
acker@commands~grepping-for-a-needle-in-a-haystack:~$ grep "pwn.college" /challenge/data.txt
pwn.college{E06LP6wkGa9eav21W5K3u_WSarl.ddTM4QDLxAjN0czW}
```