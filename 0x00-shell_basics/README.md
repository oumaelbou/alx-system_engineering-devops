task 0: script that prints the absolute path name of the current working directory
#pwd
task1: scipt that Display the contents list of your current directory
#ls
task2: script that changes the working directory to the user’s home directory
#cd ~
task3:script that Display current directory contents with details
#ls -l
task4: script that Display current directory contents, including hidden files, with details
#ls -al
task5: script that Display current directory contents, including hidden files, with details and with user and group IDs displayed numerically
#ls -al -n
task6: script that creates a directory named my_first_directory in the /tmp/ directory
#mkdir /tmp/my_first_directory
task7: script that Move the file betty from /tmp/ to /tmp/my_first_directory
#mkdir /tmp/betty /tmp/my_first_directory
task8: script that Delete the file betty in /tmp/my_first_directory
# rm -r /tmp/my_first_directory/betty
task9: script that Delete the directory my_first_directory that is in the /tmp directory.
rmdir /tmp/my_first_directory
task10: script that changes the working directory to the previous one.
#cd -
task11: script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
#ls -al . .. /boot
task12: script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
#file /tmp/iamafile
task13: script that Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
#ln -s /bin/ls __ls__
task14: script that Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
#cp -u *.html ..
