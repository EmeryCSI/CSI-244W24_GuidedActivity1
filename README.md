# Renton Technical College CSI-244
<br />    

<div align="center">  
    <img src="logo.jpg" alt="Logo">
    <h3 align="center">Guided Activity 1</h3>
</div>

This repository is a part of CSI-248 at Renton Technical College.

## Guided Activity Part 1 Using the Command Line
We will complete this assignment together in class. If you are having problems with this assignment please refer to the lecture recording.

1. Clone the repository to your local machine.
2. Make note of the folder where you cloned the repository.
3. Launch powershell by hitting the windows key and typing `powershell` and then hit enter.
4. Once inside of powershell you can your current directory with the `pwd` command. This stands for print working directory.
5. You can view the contents of the current directory with the `ls` command
6. In order to change to a different working directory you can use the `cd` command. This stands for change directory.
7. `cd` can be used to go to a specific folder, for example.

    ```powershell
    cd c:\RTC\CSI-244\Week1\
    ```
8. `cd` can also be used to back out of a folder. `cd ..` will take you up one folder. For example if you are currently in c:\Users\Jemery the `cd..` command will take you to c:\Users\

    ```powershell
    cd ..
    ```

9. `cd ~` will take you to what is referred to as the home folder. This is your windows users folder located at C:\Users\YourUserName\
10. `cd \` will take you to the root folder of your hard drive or C:\
11. When using cd to change folders you can use the `tab` key to auto complete a command. For Example let's say I wanted to navigate to C:\RTC\CSI-244\Week1\. I could start by typing `cd C:\R` and then hit `tab`. Powershell will try to find a Folder inside of C:\ that begins with the letter R. If none exists there will be no suggestion, if more than one exists than it will choose the first alphabetically. I can then repeat the processs for an folders within C:\RTC\
12. This will vary based on your file structure but my command could look something like this cd c:\R `tab to complete` Then type C `tab to complete` then W `tab to complete`
13. Getting used to this takes some time but it is a huge time saver and will cut down on typos.
14. After you have cloned this repository navigate to your local repository using the cd command.
15. Open the repository in Visual Studio Code by typing `code .`.
16. Open the terminal in Visual Studio Code by hitting ctrl + \` or cmd + \` on mac.
17. This is powershell running inside of Visual Studio Code.
18. Create a new folder called myfiles with the mkdir command (make directory)

    ```powershell
    mkdir myfiles
    ```
19. Run the ls (list) command to see your newly created folder.
20. cd into the myfiles directory

    ```powershell
    cd myfiles
    ```
21. Create a new text file using the terminal. This command will create a new file named hello.txt

    ```powershell
    new-item hello.txt
    ```
22. To open the new text file inside of visual studio code type

    ```powershell
    code hello.txt
    ```

23. Inside of the file type your name and save the file.
24. Go back to the terminal and type `cat hello.txt`.
25. Notice that your name has been displayed in the console.
26. When making a github commit via the command line make sure to back out to the repository folder before creating the commit.

    ```powershell
    cd ..
    ```
27. You should now be back inside of the root folder of the repository. If you are not sure you can always check first by typing

    ```powershell
    pwd
    ```
28. Type `git add .` to stage all updated files.
29. Type `git status` to view all staged files.
30. Type `git commit -m "Part 1 Complete"`.
31. Type `git push` to push the changes to GitHub.

## Guided Activity Part 2 Installing NVM and Node

1. Install NVM for your operating system. Windows users (https://github.com/coreybutler/nvm-windows/releases/download/1.1.11/nvm-setup.exe) Mac Users: https://dev.to/ajeetraina/how-to-install-and-configure-nvm-on-mac-os-5fgi
2. Once NVM is installed type nvm at your terminal. You should see a list of commands.
3. Type `nvm install latest` - This will install the latest version of NodeJS on your machine.
4. Type `nvm use latest`, take a screenshot of the output and add to the screenshots folder. 
5. With the latest version of NodeJS added you should now be able to run Nodel commands from the terminal.
6. Type `node --version` - A version of node should be printed to the terminal.

7. With node installed, lets try it out. For Windows, type `new-item helloworld.js` to create a new file.  For Mac, type `touch hellworld.js` to create a new file.
8. Type `code helloworld.js` to open the new file in visual studio code.
9. Add the following code to hellworld.js

    ```javascript
    console.log("Hello from helloworld.js");
    ```

11. Now from the terminal run `node helloworld.js`, Take a screenshot of the output and save to the screenshots folder. ![Guided Activity Part 2 - Step 9](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/8f4f9ddc-bfb1-43fa-ba24-35a23d79b328)

12. Type `git add .` to stage all updated files. 
13. Type `git commit -m "Guided Activity 1 Complete"`.
14. Type `git push` to push the changes to GitHub.

If you have any questions about this assignment please reach out to myself or our TA for this course. 



Feel free to message your instructor or the TA on Canvas if you have any questions.
