# svn-demo
![image](https://github.com/bqminh30/svn-demo/assets/64219602/74f4066e-8789-4fa7-bc21-43ab22607b22)
1. In Apache Subversion, commands are entered via a terminal window. To open this in Windows, press the 'Windows key' and 'r.' This will bring up the 'Run' dialog box. Enter 'cmd' and hit 'Ok.'
The terminal window will now open, ready for you to input your commands
![image](https://github.com/bqminh30/svn-demo/assets/64219602/9ec9e247-54b2-4c79-86d7-5ec11c536d7f)
![image](https://github.com/bqminh30/svn-demo/assets/64219602/eea4c479-c298-43cf-9eb4-c2b82a01afa7)
2. To create your first repository, use the 'svnadmin create' command followed by the path where you wish to create the new repository, and the name of your new repository. For example, if you wanted to create a new repository called 'New project' in the 'Documents' folder, the command would be: svnadmin create C:\Users\Jessica\Documents\New_Project
![image](https://github.com/bqminh30/svn-demo/assets/64219602/78f5f9c2-cee4-43ae-b906-a30d147856c8)
3. Check in the 'Documents' folder. You will see a new folder called 'New Project.'
![image](https://github.com/bqminh30/svn-demo/assets/64219602/24435def-0651-451a-b58f-bda3295f22e2)
4. This folder contains some new files. Do not delete or modify any of these files.
![image](https://github.com/bqminh30/svn-demo/assets/64219602/023cfafb-30e3-4822-b927-df37ba703674)
5. Now you have created a repository, checkout a working copy. This is done using the 'SVN Checkout' command, followed by the URL of your repository and the location of the repository you just created on your computer. In this example, the command is: svn checkout http://127.0.0.1:9880/New-Project C:\Users\Jessica\Documents\New_Project Hit 'Enter.'
![image](https://github.com/bqminh30/svn-demo/assets/64219602/563f7327-0907-4cf1-9dff-123f8756ec72)
6. When you check your working copy, you will notice copies of all the files from your repository.
![image](https://github.com/bqminh30/svn-demo/assets/64219602/d289accf-043b-4487-bf94-f163db63249b)
7. Now you are free to make changes to your working copy. When you have finished modifying your files, you will need to commit your changes back to the repository. To perform a commit, use the 'svn commit' command followed by “--message” and an appropriate log message, and finally, the location of your working copy. In this example, the command would be: svn commit --message “added Readme file” C:\Users\Jessica\Documents\New_Project Hit 'Enter.' Your changes have now been committed to the repository!

