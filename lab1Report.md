# CSE 15L, Lab Report 1: Remote Access and Filesystem
## Lucas Venetoulias 
## Jan. 16th, 2023


<ins> Part 1: Installing VScode </ins>
Copy [this link](https://code.visualstudio.com/) to the Visual Studio Code website and follow the webpage instructions for downloading VScode on your local computer. Be sure to download the version of VScode that corresponds with your computer’s operating system (e.g. OS, Linux, Windows). 
Then follow any installation instructions on your local computer to open VScode on your computer. (Note: instructions may vary slightly depending on the operating system of your computer.) Once you open VScode, you should see a screen similar to the following image, with some minor differences depending on computer and program settings):
![VScode success](/cse15l-lab-reports/VScode.setup.jpg)


<ins> Part 2: Establishing Remote Access </ins>
Before continuing with VScode, find your course-specific account (you can find this by going to the Account Lookup form and entering your username and PID). The course-specific account should be of the form *cs15lwi23abc*, where *abc* are specific letters that correspond only to your account.
![image](https://user-images.githubusercontent.com/122565720/212186092-1db33157-9975-4200-b7f0-0771accd8556.png)
After you have identified course-specific account, open a new Terminal in VScode and enter the command {% highlight yellow %} ssh cs15lwi23abc@ieng6.ucsd.edu {% endhighlight %}, where the email address before the ‘@’ symbol is your course-specific account. When prompted, enter your password (it might be the same as your PID password). Once the password has been entered successfully, something like the following should appear in the terminal:
![image](https://user-images.githubusercontent.com/122565720/212186214-68e0158f-5f31-453f-b477-eba793fb1d72.png)


<ins> Part 3: Entering Commands </ins>
Now that you have connected through remote access, you can now begin to try some terminal commands. Some of the more common commands include:
* {% highlight yellow %} cd <path>  {% endhighlight %} (to move you to a different directory)
* {% highlight yellow %} ls  {% endhighlight %} (to provide a list of all files and folders present in the current directory)
* {% highlight yellow %} pwd  {% endhighlight %} (to print the current working directory)
* {% highlight yellow %} scp  {% endhighlight %} (to create a secure copy of a file or directory)
Here are a couple of more to try out:
•	{% highlight yellow %} cd ~  {% endhighlight %} (to take you to the home directory, either on the remote or the local computer)
•	{% highlight yellow %} cat <path/file>  {% endhighlight %} (to print out the contents of simple files where the file is identified through the path)
Below are a couple of examples of these commands and the results they produce:
**IMAGEs GOES HERE**
Great! Now you have tried a couple of commands through the terminal and you want to exit. To log out of the terminal and disconnect, simply run the command {% highlight yellow %} exit {% endhighlight %}.






