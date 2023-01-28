Kevin Yu
CSE 15L
1/15/23
Lab 1

Hello! if you are a new student in CSE15L then this blog post can help you with how to properly set up your CSE15 account and create a github account.

One of the first applications you will need to have installed on your machine is VS code, before that verify that java is installed on your computer then navigate
to [this page](https://code.visualstudio.com/) and select install and make sure the version matches with the operating system for your machine.

After downloading VS code and launching it the application should look like:

![image](https://user-images.githubusercontent.com/122575342/212788027-ab0a487b-eb1f-4232-b9e8-8df7d983fd1b.png)



Next, we are going to need to set up your course specific account for CSE15. To do this, navigate over to [this site](https://sdacs.ucsd.edu/~icc/index.php) and follow the steps
to reset your passowrd, it is important that you do not change the global password as that will switch the login info for all of your UCSD related accounts. 

The screen should look something like this

![image](https://user-images.githubusercontent.com/122575342/212785770-26c2383d-71f1-4ca2-8e0e-fd22d5d3fcc6.png)

you will then click the additional accounts to set your password for your CSE15L account and after resetting, it will take around 15 minutes for the password change to take effect 

Once your password is set, open up a terminal on VS code and enter the command, $ ssh cs15lwi23zz@ieng6.ucsd.edu however replace the "zz" with the characters found in your username. This will allow you to remotely connect and you should be able to see a new internface displaying that your device is now connected.

The terminal should look like: 

![image](https://user-images.githubusercontent.com/122575342/212787325-29cfd604-1845-4100-aed2-80453d4bc59c.png)

After connecting, the final step is for you to try some commands and some that you can try are listed below:

cd ~
cd
ls -lat
ls -a
ls <directory> where <directory> is /home/linux/ieng6/cs15lwi23/cs15lwi23abc
cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/
cat /home/linux/ieng6/cs15lwi23/public/hello.txt
exit

After this you have sucessfully remotely connected and completed all the steps!


