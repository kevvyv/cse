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

`cd ~`
> Output:
![image](https://user-images.githubusercontent.com/122575342/215357476-63794963-d969-4c5c-862e-488ee924a647.png)


`cd`
> Output: 
![image](https://user-images.githubusercontent.com/122575342/215357476-63794963-d969-4c5c-862e-488ee924a647.png)
> cd~ is used to go back a directory and can be useful to navigate to a previous point quickly.

> Cd is used to change directories and this is useful to navigate and choose the location one desires to conduct their programming in

`ls -lat`
> This code will generate an output like:
![image](https://user-images.githubusercontent.com/122575342/215356816-44509b14-e415-44a2-bafd-c5209d961c1e.png)
What is occuring in the output is that the terminal is returning all the files in the current directory. One is also able to see
that the username is also displayed so it can be noted that since the username matches, we are looking at the files on my account.

`ls -a`
> The output is: 
![image](https://user-images.githubusercontent.com/122575342/215357330-6ced27fc-072c-4d81-89a8-0710def18e61.png)
This output is informing the user of all the current directories and files the user has acess to. This can be useful to view before deciding what directory
you would want to switch to.

`ls <directory> where <directory> is /home/linux/ieng6/cs15lwi23/cs15lwi23ajs`
> Output:
![image](https://user-images.githubusercontent.com/122575342/215357558-846f4071-8f2d-4afc-b840-f39ead7929e1.png)

This command attemps to acess a directory given the specified path and in this case the output is now allowing the user to gain acess to this directory

`cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/`
> Output: 
![image](https://user-images.githubusercontent.com/122575342/215357797-d951e20a-1ea1-406b-872e-df2135b4c6fe.png)
This command creates a copy of the designated file and it could be useful if a user wanted to edit a file without risk of distrupting the original file

`cat /home/linux/ieng6/cs15lwi23/public/hello.txt`
> Output:
![image](https://user-images.githubusercontent.com/122575342/215357906-db44fc03-dcea-4cdb-be0c-7d0c352c7d1f.png)
This command concatinates the assigned file while also viewing the contents inside the file and in this case displayed the text that was in the file. This is an extrmely useful command as accessing a files properties is crucial in many programs.

`exit`
> Output:
![image](https://user-images.githubusercontent.com/122575342/215358309-a51e9ad9-4f22-4757-a1c3-c7da665008d6.png)
This command exits the user from their remote connection and is useful when a user wants to quit out of their connection when they are done programming.



After this you have sucessfully remotely connected and completed all the steps!

  


