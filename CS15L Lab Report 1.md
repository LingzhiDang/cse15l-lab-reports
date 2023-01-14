•	Installing VScode

To install VScode, you need firstly searched VScode on Google or go to https://code.visualstudio.com/Downloadand select the right version for your PC
(for example, my PC is windows x64). 
![image](https://user-images.githubusercontent.com/59113479/212490736-41a4e91c-3e00-4872-aa5e-3fbd67d74caf.png)

Then you need to follow the install procedures and you may change the default options for your own considerations and needs. 
(If space is available, you may select C:\\ for windows to install to avoid some unknown errors).
This is the default situation of VScode, if you can open your VScode an see something like this. Congratulations!
![image](https://user-images.githubusercontent.com/59113479/212489754-bea98b1c-f9c1-4325-b1fa-f05223f80570.png)

•	Remotely Connecting

Firstly, If you use windows PC, you need to install a git bash to start remote connect.
Gitbash: https://gitforwindows.org/
Please install Git bash at the default folder

Here is a good guidance I used to invite git bash to vscode
https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994

Basically, you need to open the terminal and command palate at setting, and then type “Select default options”. Choose Git bash and select bash at your terminal then restart your VScode to check Whether the bash icon is there.
![image](https://user-images.githubusercontent.com/59113479/212489781-a9a13c3c-00a8-4fe2-af63-0f3328cafabd.png)
![image](https://user-images.githubusercontent.com/59113479/212489783-aa594846-6484-4609-9eab-cc0b9a1e5845.png)

Then you can try to open the terminal and use command “ssh cs15lwi23avg@ieng6.ucsd.edu” in the terminal to invoke the remote connect and type your password
Notice: You need to change “avg” here to your own letter in course-specific account. The format is your own account name + “@ieng6.ucsd.edu”. You many copy the command in sample and change the “avg” part and paste to the terminal.

Notice: you need to give the authenticity to host because it’s the first time you connect. You will see 

The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
Are you sure you want to continue connecting (yes/no/[fingerprint])?
Typing “Yes” to connect and then type your password

If it is successful, you will see something like that.
![image](https://user-images.githubusercontent.com/59113479/212489790-dcc79327-55c1-46c7-a250-c042e82e9e08.png)

(It is not my first time to connect, so I do not need to give the authenticity)

Then you need to type your own password for your student account. You will not see what you 
are typing here. Please make sure you type your password correctly without any change and press
“enter” when you finish. If you connect successfully, you will see something like this.
![image](https://user-images.githubusercontent.com/59113479/212489798-a41f1468-4334-4e99-978d-3a0244cd97a8.png)
Congratulation! That means you connect successfully.

•	Trying Some Commands

Now try some commands in terminal. Here are some examples of commands for you.

cd

cd~

ls -lat

ls -a

cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/

cat /home/linux/ieng6/cs15lwi23/public/hello.txt

There is a remote file, 
if you type the last command and get a sentence, it means you load the file.
![image](https://user-images.githubusercontent.com/59113479/212489819-b81b14dc-55e0-4226-bb91-cf6e07898b4c.png)

Congraduation! Here are all you need to do for remotely connecting part.Good job!


