# Lab Report 1
## Remote Access: SSH, accessing course specific account

1. **Installing IDE** (integrated development enviroment)
In this class we use Visual Code Studio (VScode) as our IDE. To install, following the instructions on the [VSCode website](https://code.visualstudio.com/). 
Installation differs depending on operating system (windows --> PCs, macOS --> macs). After downloading, open the application. The windown should look like the one below:
(Note: the background color is a mattter of preference)
![Image](VSCode.png)

2. **Accessing course specific account**
In this tutorial, we will be connecting to a reomte computer through VScode and the local computer terminal to connect over the internet. 
In order to SSH into the ieng6 server, you need to access your course specific account. This can be found [here](https://sdacs.ucsd.edu/~icc/index.php).
Once you have your account username, which should look something like cs15l<quarterAbriviation><last2DigitsYr><uniqueIdentifier>, you will need to reset the password. 
Follow this [tutorial](https://drive.google.com/file/d/17IDZn8Qq7Q0RkYMxdiIR0o6HJ3B5YqSW/view). 

3. **Remotely connecting**
- Next we need to SSH into the computers in the CSE basement. To do this open a terminal in VSCode (ctrl/command + ' alternatively terminal --> new terminal from the menu bar)
- In the terminal in VSCode, type the command: 
```
$ ssh cs15lsp23<uniqueIdentifier>@ieng6.ucsd.edu
```
- replace the <unique identifier> with the coresonding letters from you previously found course specific account. (Note: the $ isn't part of the command, it only signifies a command)
*If this is your first time connecting to the server you will likely recieve a message about authenticity of the host 'ieng6...' you can say yes to this message.
When the SSH command is typed into the local computer terminal, it should look like the following:
![Image](SSHinTermianl.png)
When the SSH command is typed into the VScode terminal, it should look like the following:
![Image](SSHVSTerminal.png)
This means that your remote computer is connected to the CSE basement, therefore commands run on your computer terminal will be run on that CSE basement computer. Your computer is the **client** and the CSE basement computer is the **server** based on the above connection.
  
## Running Commands
- Next we will try running some commands in the terminal. Here are some listed to try:
![Image](commands.png)
![Image](commandFromLab.png)
- When completing the asignment I tried the following commands chosen from the lab write up suggestions:
![Image](ExampleCommands.png)
