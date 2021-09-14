## Question 1
Write a shell script that does the following:
1. Create a directory called "hw1q1".  
2. Copy the "hw1q1" directory to another directory called "hw1q1_copy".  
3. Create an empty file in "hw1q1_copy" called "f1.txt".
4. Copy that file to "hw1q1" and rename it "f1_copy.txt".
5. Repeat step 4 except name the file "f1_copy2.txt".
6. List out the directories created along with everything in question1 folder.
7. List out the files in the "hw1q1" directory.

Hint: "../" goes back one directory

Compilation Steps:  
Make a directory using mkdir hw1q1; copy hw1q1 and rename copy as hw1q1_copy; create a blank file with touch f1.txt; move f1_copy.txt back one directory to hw1q1; copy f1.txt and rename copy to f1_copy2.txt; move f1_copy 2.txt back to hw1q1; move back a directory with cd ../; list directories with ls; move into hw1q1 with cd hw1q1; and list files in long format.
cp -R hw1q1 hw1q1_copy
cd hw1q1_copy
touch f1.txt
cp f1.txt f1_copy.txt
mv f1_copy.txt ../hw1q1
cp f1.txt f1_copy2.txt
mv f1_copy2.txt ../hw1q1
cd ../
ls
cd hw1q1
ls -l
Output:
