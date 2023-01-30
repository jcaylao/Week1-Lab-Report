# **Remote Access**

## **Find Your CSE15L Account**
1) Click on the link [Link](https://sdacs.ucsd.edu/~icc/index.php) and input your information into the Account Lookup section

2) After you input your information, you should see your CSE15L account username.

3) Click on your username and reset your password by clicking on *change your password*, then follow the instructions shown

4) Make sure to write down your username and password somewhere so that you will not forget it.


## **How to Install VScode**
1) Click on the link to go to the Visual Studio Code download site [Link](https://code.visualstudio.com/Download)

2) Select the correct version for your device ![Image](https://github.com/jcaylao/Week1-Lab-Report/blob/main/Screenshot%202023-01-12%20171359.png?raw=true)

3) Follow the download instructions and then open up the Visual Studio Code app. You should see this on your screen ![Image](https://github.com/jcaylao/Week1-Lab-Report/blob/main/Screenshot%202023-01-12%20170018.png?raw=true)


## **Remotely Connecting**
1) Install git for Windows [Link](https://git-scm.com/download/win)

2) Open Visual Studio Code and open the terminal by pressing and holding the `ctrl` and `'`  key. If this shortcut does not work for you, you can manually open a new terminal by following along with the image below ![Image](https://github.com/jcaylao/Week1-Lab-Report/blob/main/Screenshot%202023-01-12%20174524.png?raw=true)

3) Open the command palette by pressing the *ctrl + shift + p*  key

4) Search up *Select Default Profile*. Then Select Git Bash.

5) Once you select Git Bash, wait a few seconds then click on the `+` symbol on the terminal. This is what your terminal should look like ![Image](https://github.com/jcaylao/Week1-Lab-Report/blob/main/Screenshot%202023-01-13%20140759.png?raw=true)

6) Type into the terminal this command: `$ssh (your course specific account)@ieng6.ucsd.edu`

7) When logging into a new server, you will get a verification message that will ask you to type in a response. Type *yes*. This is what you should see on your screen ![Image](https://github.com/jcaylao/Week1-Lab-Report/blob/main/Screenshot%202023-01-14%20165031.png?raw=true)

8) Then it will prompt you to put in your password. When typing, the letters will not appear on the screen but once you press enter this is what you should see. If the password was incorrect it will continue to ask you to enter your password.
![Image](https://github.com/jcaylao/Week1-Lab-Report/blob/main/Screenshot%202023-01-14%20170415.png?raw=true)

If this is what you see then you have successfully connected to the server!


## **Try Some Commands**
Now that you have connected remotely, you can now put in commands. Here are some that you can try:
`cd ~`

`cd`

The cd command changes the working directory and I found it interesting that there would be no output displayed, but this meant that the command ran successfully.

`ls -lat`

`ls -a`

The ls command was interesting because I did not know what the command would do, but after inputting it into the terminal I was able to realize that the ls command would show all of the files in the directory in a list.

`cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/`

`cat /home/linux/ieng6/cs15lwi23/public/hello.txt`

I found the cp command to be interesting because I thought it was fascinating how I am able to copy a file from a different device without having to physically connect to it.

In this step I just inputted some codes into the terminal to see the different outputs each command would do. After inputting each command, I learned about the different outputs and why I should use different ones.
Here are some example outputs: 
![Image](https://user-images.githubusercontent.com/122569462/212506872-da8cffdc-02e6-4771-bd95-44c5291093b1.png)
![Image](https://user-images.githubusercontent.com/122569462/215378449-2ecfd65c-194a-49cd-9a95-3a2e014f376d.png)

## **Logging out**
To log out of the remote server, press `ctrl` + `-` + `D` then type *exit*.
