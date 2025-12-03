# LinuxBasics
ubuntu:~/C/maths$ cd ../..
ubuntu:~$ ls
A  B  C  D  Subjects  filesystem  script.sh  script2.sh
ubuntu:~$ ls C/
computer  maths
ubuntu:~$ ls C/maths/
HigherMathematics.txt
ubuntu:~$ ^C
ubuntu:~$ cat script2.sh 
#!/bin/bash
mkdir C
cd C
mkdir maths
mkdir computer
cd maths
touch HigherMathematics.txt
cd ..
cd ..

ubuntu:~$ ^C
ubuntu:~$ cat C/maths/HigherMathematics.txt 
ubuntu:~$ vi C/maths/HigherMathematics.txt 
ubuntu:~$ cat C/maths/HigherMathematics.txt 
This is a book on Higher Mathematics.
Table of Contents - 
1. Calculas - Integration, Differentiation
2. Discrete Mathematics
3. Graph Theory
ubuntu:~$ ^C
ubuntu:~$ cat script.sh 
#!/bin/bash
mkdir Subjects
cd Subjects
mkdir civics
mkdir physics
cd civics
touch The Constitution.txt
cd ..
cd ..

ubuntu:~$ cat script2.sh 
#!/bin/bash
mkdir C
cd C
mkdir maths
mkdir computer
cd maths
touch HigherMathematics.txt
cd ..
cd ..

ubuntu:~$ 
