NAME: FmtString

DESC:
What's the worst that can happen with a program that just echoes the input?


SSH into this server to try to break the binary:
IP = 13.54.79.17 
username: test
password = password

POINTS:
111

compiled with:
gcc -ggdb -m32 -fno-stack-protector -z execstack