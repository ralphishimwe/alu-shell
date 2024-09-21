1. 0-current_working_directory: This file contains script when executed it will print the current working directory
./0-current_working_directory pwd
2. 1-listit This file contains script for listing all files in working directory
./1-listit ls
3. 2-bring_me_home this script is used to take to home directory  cd ~
4. 3-listfiles used to list files in long format ls -l
5. 4-listmorefiles list all files ls -la
6. 5-listfilesdigitonly list all file in long format numerically instead of names ls -lan
7. 6-firstdirectory script that creates a directory named my_first_directory in the /tmp/ directory.mkdir /tmp/my_first_directory to
verify: file /tmp/my_first_directory/ output: /tmp/my_first_directory/: directory
8. 7-movethatfile how to move file first create it touch: /tmp/betty, move it mv /tmp/betty /tmp/my_first_directory/ verify: ls /tmp/my_first_directory/
9. 8-firstdelete deleting the betty file rm /tmp/my_first_directory/betty
10. 9-firstdirdeletion deleting directory rmdir /tmp/my_first_directory
11. 10-back change back to the last directory command: cd -, source ./10-back to check and you to make the dir you are trying to back from has 10-back file so the ./ can find it create it again.
12. 11-lists since you can't use &&,;,|| to combine commands instead you used ls -la . .. /boot
13. 12-file_type to open file: file /tmp/iamafile first create it touch /tmp/iamafile
