# Renton Technical College CSI-248
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
    new-item hello.txt`
    ```
22. To open the new text file inside of visual studio code type

    ```powershell
    code hello.txt
    ```

23. Inside of the file type your name and save the file.
24. Go back to the terminal and type `cat hello.txt`.
25. Notice that your name has been displayed in the console.
30. Take a screenshot of the output and save the file inside of the screenshots folder.
31. Type `git add .` to stage all updated files.
32. Type `git status` to view all staged files.
33. Type `git commit -m "Part 1 Complete"`.
34. Type `git push` to push the changes to GitHub.

## Guided Activity Part 2 Node NVM and Node

1. Install NVM for your operating system. Windows users (https://github.com/coreybutler/nvm-windows/releases/download/1.1.11/nvm-setup.exe) Mac Users: https://dev.to/ajeetraina/how-to-install-and-configure-nvm-on-mac-os-5fgi
2. Once NVM is installed type nvm at your terminal. You should see a list of commands.
3. Type `nvm install latest` - This will install the latest version of NodeJS on your machine.
4. Type `nvm use latest`, take a screenshot of the output and add to the screenshots folder. 
5. With the latest version of NodeJS added you should now be able to run Nodel commands from the terminal.
6. Type `node --version`, take a screenshot of the output and add to the screenshots folder. ![Guided Activity Part 2 - Step 6](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/8798059e-1c5a-49fc-b964-2697973e1dff)

7. With node installed, lets try it out. For Windows, type `new-item helloworld.js` to create a new file.  For Mac, type `touch hellworld.js` to create a new file.
8. Inside of that file in Visual Studio Code add `console.log("Hello World");` to the file and save it. ![Guided Activity Part 2 - Step 8](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/4c88a379-303c-47b5-a6c9-abb8d00211df)

9. Now from the terminal run `node helloworld.js`, Take a screenshot of the output and save to the screenshots folder. ![Guided Activity Part 2 - Step 9](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/8f4f9ddc-bfb1-43fa-ba24-35a23d79b328)

10. Type `git add .` to stage all updated files. 
11. Type `git commit -m "Part 2 Complete"`.
12. Type `git push` to push the changes to GitHub.

## Guided Activity Part 2 NPM
1. From the terminal type `npm init` (this creates a new node project)
2. Name the package firstnodeproject. ![Guided Activity Part 2 NPM - Step 2](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/92062331-5043-4bd4-b404-3fdada89ff08)

3. You can simply hit enter for all of the additional options. ![Guided Activity Part 2 NPM - Step 3](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/ff67983c-1982-404c-b6c7-0fc15f38ee81)

4. Notice that a package.json file is created. 
5. package.json defines the entry point of the application as well as an dependencies the project may have.
6. Notice that helloworld.js is defined as main, or the entry point. ![Guided Activity Part 2 NPM - Step 6](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/db29fded-8c28-4e28-bedf-075d385c90b2)

7. Lets create an index.js file.
8. For Windows, type `new-item index.js`.  For Mac, type `touch index.js`. ![Guided Activity Part 2 NPM - Step 8](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/dd24f55e-79f9-4fca-bbd8-d18b9ce2a456)

9. Open index.js in Visual Studio code and add `console.log("Node project running");` and save the file. ![Guided Activity Part 2 NPM - Step 9](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/ef76cf5e-c064-4553-9d16-d9d937dfa644)

10. Now let's tell Node to run index.js when we start the project.
11. Open package.json and replace the entry under scripts `"test": "echo \"Error: no test specified\" && exit 1"` with `"start" : "node index.js"`. ![Guided Activity Part 2 NPM - Step 11](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/1a728543-02f1-4b51-a765-764e4c4cce98)

12. Save the file.
13. Now run npm start from the terminal. You should see Node Project Running printed to the console. ![Guided Activity Part 2 NPM - Step 13](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/0fa17b5e-0e99-42cd-966e-83ee5509b7f8)

14. Take a screenshot of the output and add to the screenshots folder. ![Guided Activity Part 2 NPM - Step 14](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/b7a93d29-aab5-48cf-adf1-efc8f3638e53)

15. Type `git add .` to stage all updated files.
16. Type `git commit -m "Guided Activity 1 Complete"`.
17. Type `git push`.

If you have any questions about this assignment please reach out to myself or our TA for this course. 



Feel free to message your instructor or the TA on Canvas if you have any questions.
