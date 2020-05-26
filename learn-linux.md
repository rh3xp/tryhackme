# Learn Linux

Page : [Learn Linux](https://tryhackme.com/room/zthlinux)

#### Task 33

Find the executable `shiba4` to get the password.

`find / -executable -name shiba4 -print 2>/dev/null`
> does not print errors

`shiba4:test1234`


