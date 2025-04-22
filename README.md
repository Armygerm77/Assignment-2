# Assignment-2
ssh-keygen -t ed25519 -C "Assignment 2"
git remote remove origin
git remove add origin <url>
git fetch assignments-base
git remote add assignments-base git@github.com:cu-ecen-aeld/aesd-assignments.git 
git merge assignments-base/assignment2
git submodule update --init --recursive
git push origin main
touch assignments/assigment2/cross-compile.txt
-print-sysroot- -v
finder-app/finder-test.sh 
./full-test.sh 
