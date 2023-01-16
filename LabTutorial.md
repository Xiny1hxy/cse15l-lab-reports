# Part1: Installing VScode
To install the Visual Studio Code, please visit the website [VScode](https://code.visualstudio.com/), and follow the instructions to download VScode to your computer. (For Mac users, remember to move VScode to your table)

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
(Remember to replace `zz` with your own course-specific account. You don't need to type in `$`, we wrote `$` to help you the recognize that this is an command)
You will get a message like this: 
```
⤇ ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
```
(This message should only occur when you are connecting to a new server for the first time)
Type `yes` to continue the connection to the server. 
3. Your terminal will request for the password, (the new passsword that you just reset for the course-specific account),
```
# On your client
⤇ ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6-202.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
Password: 
```
Enter the password and you will receive a message like this:
```
# Now on remote server
Last login: Sun Jan  2 14:03:05 2022 from 107-217-10-235.lightspeed.sndgca.sbcglobal.net
quota: No filesystem specified.
Hello cs15lwi23zz, you are currently logged into ieng6-203.ucsd.edu

You are using 0% CPU on this system

Cluster Status 
Hostname     Time    #Users  Load  Averages  
ieng6-201   23:25:01   0  0.08,  0.17,  0.11
ieng6-202   23:25:01   1  0.09,  0.15,  0.11
ieng6-203   23:25:01   1  0.08,  0.15,  0.11

Sun Jan 02, 2022 11:28pm - Prepping cs15lwi23
```
(This is a message from the remote server)


