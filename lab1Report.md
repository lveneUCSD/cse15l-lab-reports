# CSE 15L, Lab Report 1: Remote Access and Filesystem
## Lucas Venetoulias 
## Jan. 16th, 2023


<ins>Part 1: Installing VScode:</ins>
<br> Copy [this link](https://code.visualstudio.com/) to the Visual Studio Code website and follow the webpage instructions for downloading VScode on your local computer. Be sure to download the version of VScode that corresponds with your computer’s operating system (e.g. OS, Linux, Windows). 
Then follow any installation instructions on your local computer to open VScode on your computer. (Note: instructions may vary slightly depending on the operating system of your computer.) Once you open VScode, you should see a screen similar to the following image, with some minor differences depending on computer and program settings):
![VScode success]
<img width="468" alt="image" src="https://user-images.githubusercontent.com/122565720/212587662-eec670b5-ac34-4759-b720-0b8889b84e9f.png">



<ins>Part 2: Establishing Remote Access</ins>
<br> Before continuing with VScode, find your course-specific account (you can find this by going to the Account Lookup form and entering your username and PID). The course-specific account should be of the form *cs15lwi23abc*, where *abc* are specific letters that correspond only to your account.
After you have identified course-specific account, open a new Terminal in VScode and enter the command **ssh cs15lwi23abc@ieng6.ucsd.edu**, where the email address before the ‘@’ symbol is your course-specific account that you just found. When prompted, enter your password (it might be the same as your PID password). Once the password has been entered successfully, something like the following should appear in the terminal:


<ins>Part 3: Entering Commands</ins>
<br> Now that you have connected through remote access, you can now begin to try some terminal commands. Some of the more common commands include:
* **cd path** (to move you to a different directory, where path is the path to that particular directory)
* **ls** (to provide a list of all files and folders present in the current directory)
* **pwd** (to print the current working directory)
* **scp** (to create a secure copy of a file or directory)
<br> Here are a couple of more to try out:
*	**cd ~** (to take you to the home directory, either on the remote or the local computer)
*	**cat <path/file>** (to print out the contents of simple files where the file is identified through the path)
<br> Below are a couple of examples of these commands and the results they produce:
**IMAGEs GOES HERE**
<br> Great! Now you have tried a couple of commands through the terminal and you want to exit. To log out of the terminal and disconnect, simply run the command **exit**.






