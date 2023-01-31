**CSE 15L Week 1 Lab Report**
<br>
**Seungki Kim**

<br><br>
**Installing VSCode**
1. First, visit the [official website for installing Visual Studio Code](https://code.visualstudio.com/). You can click the blue link to visit the website.
Here, you will find the button for downloading VSCode according to your OS. I’m currently using Windows, so I will download the installer for Windows x64.
![](https://cdn.discordapp.com/attachments/890102969536753746/1069854007419473950/image.png)

<br>

2. After clicking the download button, it should automatically start downloading the installer for VSCode. Click the installer program when it is done.


<br>

3. Click “Agree” on the License Agreement page, and then click next to proceed.


<br>

4. VSCode installer will suggest an additional task selection page, but you can just click next if there aren’t any additional tasks you need. Then, press install to finish the installation.



**Remotely Connecting**
1. Before starting, Windows users need to [download git for Windows](https://gitforwindows.org/). Git comes with tools that are necessary for this step.

2. If git has been downloaded, you need to set the git bash as a default terminal in VSCode. Enter VSCode and open the terminal by pressing ``Ctrl + ' `` or ``Terminal -> New Terminal`` in the top menu bar.
![](https://cdn.discordapp.com/attachments/890102969536753746/1069854590935240704/image.png)

<br>

3. Open the command palette by pressing ``Ctrl + Shift + P`` as a shortcut, or selecting ``View -> Command Palette`` in the top menu bar.
![](https://cdn.discordapp.com/attachments/890102969536753746/1069854668873805865/image.png)

<br>

4. Type ``Select Default Profile``, and select ``Git Bash`` from the options.

5. Click on the ``+`` icon in the top right of the terminal window. I have already selected ``Git Bash`` as default terminal so it shows as Git Bash (Default).

<br>

![](https://cdn.discordapp.com/attachments/890102969536753746/1069854716730814524/image.png)

<br>

6. To remotely connect, use ``ssh`` in the VSCode terminal. The command you’re typing in would be ``ssh cs15lwi23[course-specific account]@ieng6.ucsd.edu``. The part ``[course-specific account]`` should be the letters in your own account.

7. Connecting for the first time would show a text message that looks likes this: 
    ```The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
    RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
    Are you sure you want to continue connecting (yes/no/[fingerprint])?```
  Type ``yes`` and press enter to continue.

8. Then, it will ask for a password. Use your password that you have set up before to log in.



**Trying Some Commands**
1. Try running a few commands to navigate through directories in VSCode. Type pwd and press enter. This is a print working directory command that prints out the current directory you’re in.
![](https://cdn.discordapp.com/attachments/890102969536753746/1069854770925404200/image.png)

<br>

2. Type ``ls`` and press enter. ``ls`` is a command of what files are in the current working directory. You can use this command to look for specific files that you would want to navigate through.
![](https://cdn.discordapp.com/attachments/890102969536753746/1069854805201260624/image.png)

<br>

3. You can also use ``cd`` to move your current working directory to one of the folders in that directory. For example, typing cd desktop would put yourself in a desktop folder for Windows. But keep in mind that this command wouldn’t work if the directory you typed in does not exist in your current directory.
