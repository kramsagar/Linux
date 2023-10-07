[rkyasan44@testhost commands]$ ls 1 2
1:
1.txt

2:
[rkyasan44@testhost commands]$ cp 1 2
cp: -r not specified; omitting directory '1'
[rkyasan44@testhost commands]$ cp -r 1 2
[rkyasan44@testhost commands]$ cp 1 2
cp: -r not specified; omitting directory '1'
[rkyasan44@testhost commands]$ ls 1 2
1:
1.txt

2:
1
[rkyasan44@testhost commands]$ cp 1/ 2
cp: -r not specified; omitting directory '1/'
[rkyasan44@testhost commands]$ cp -r 1/ 2
[rkyasan44@testhost commands]$ ls 1 2
1:
1.txt

2:
1
[rkyasan44@testhost commands]$ ls -ltr
total 4
lrwxrwxrwx. 1 rkyasan44 rkyasan44  9 Jun  5 11:14 file6.txt -> file1.txt
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:33 xyz
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:33 abc.txt
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:33 abc
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:34 abc2xyz
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:34 abc1xyz
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:34 abc3xyz
drwxr-xr-x. 3 rkyasan44 rkyasan44 20 Jun  5 11:39 k8s
-rw-r--r--. 1 rkyasan44 rkyasan44 10 Jun  5 11:40 1.txt
drwxr-xr-x. 2 rkyasan44 rkyasan44 19 Jun  5 11:40 1
drwxr-xr-x. 3 rkyasan44 rkyasan44 15 Jun  5 11:41 2
[rkyasan44@testhost commands]$ mv 1.txt 1
[rkyasan44@testhost commands]$ ls -ltr
total 0
lrwxrwxrwx. 1 rkyasan44 rkyasan44  9 Jun  5 11:14 file6.txt -> file1.txt
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:33 xyz
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:33 abc.txt
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:33 abc
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:34 abc2xyz
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:34 abc1xyz
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:34 abc3xyz
drwxr-xr-x. 3 rkyasan44 rkyasan44 20 Jun  5 11:39 k8s
drwxr-xr-x. 3 rkyasan44 rkyasan44 15 Jun  5 11:41 2
drwxr-xr-x. 2 rkyasan44 rkyasan44 19 Jun  5 11:42 1
[rkyasan44@testhost commands]$ mv 1 2
mv: cannot move '1' to '2/1': File exists
[rkyasan44@testhost commands]$ mv 1 3
[rkyasan44@testhost commands]$ ls -ltr
total 0
lrwxrwxrwx. 1 rkyasan44 rkyasan44  9 Jun  5 11:14 file6.txt -> file1.txt
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:33 xyz
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:33 abc.txt
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:33 abc
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:34 abc2xyz
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:34 abc1xyz
drwxr-xr-x. 2 rkyasan44 rkyasan44  6 Jun  5 11:34 abc3xyz
drwxr-xr-x. 3 rkyasan44 rkyasan44 20 Jun  5 11:39 k8s
drwxr-xr-x. 3 rkyasan44 rkyasan44 15 Jun  5 11:41 2
drwxr-xr-x. 2 rkyasan44 rkyasan44 19 Jun  5 11:42 3
[rkyasan44@testhost commands]$
