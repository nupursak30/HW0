## Steps to create a simple git hook
1. Create a local git repository inside a new directory 'simplehook' using **git init** command
2. Go inside the **.git/hooks** folder and create a new file - **[post-commit](https://github.ncsu.edu/nsakhal/HW0/blob/master/post-commit)**. Change the file permissions using **chmod +x post-commit** command in Unix Systems.  
3. Now go back to the 'simplehook' folder and create a new commit using the following steps:  
-touch hookstest.txt  
-git add hookstest.txt  
-git commit -m "Testing the post-commit hook"  
4. As soon the new commit is being made, the webpage mentioned in the [post-commit](https://github.ncsu.edu/nsakhal/HW0/blob/master/post-commit) file will be displayed. In my case, NCSU ECE Department homepage will be displayed.
