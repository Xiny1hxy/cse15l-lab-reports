# Part1: Installing VScode
To install the Visual Studio Code, please visit the website [link](https://code.visualstudio.com/), and follow the instructions to download VScode to your computer. (For Mac users, remember to move VScode to your table)

//If you have any question when downloading VScode, please visit the official download guidance [link](

When you successfully download VScode and open it, the homepage should look like this
![Image](file:///Users/kristinhu/Desktop/%E6%88%AA%E5%B1%8F2023-01-11%2011.19.16.png)
（It might not be exactly the same as mine, depand on your settings)

# Part2: Remotely Connecting
For CSE15L, your are prefered to use a course specific account that is connected to a remote computer in our institution to do work. Here are the insturctions that con help you to do the remote connection:

1. Follow the "How to Reset your Password" tutorial in your group task document to get yout course-specific account and reset the password.
2. Open the terminal in VScode using (Ctrl/Command + `), or open it manually, clicking 'Terminal' in the top menw, and do 'new Ternimal'. Use the following command to connect the server:
```
$ ssh cs15lwi23zz@ieng6.ucsd.edu
```
(Remember to replace `zz` with your own course-specific account. You don't need to type in `$`, we wrote `$` for you the recognize that this is an command)
