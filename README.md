# First-script
Before starting work with the repository, we clone the remote repository on our computer git clone <repository link> .

Сreating new directories mkdir <directory name> .

git status - command checks the status of the files in our directory .

If we have files with the "modified" status displayed, then we need to prepare these files for saving in the repository using the command git add <file name> .

If many files have the status "modified", then all of them can be saved with the command git add -A .

To display changes in the repository and save all files, create a commit with the command git commit -am "commit message text" .

Start synchronization from the local repository to the remote one with the git push command . 

With the ls -l command, we check the list of files in the directory and the rights to them .

To give permission to run a file to all types of users, use the command chmod + x <file name> .

Run the script in the terminal with the command bash <file name> with the extension .sh .

The schedule for running the script is configured through the cron daemon .

Open the cron job table with crontab -e .

At the bottom, under the informational text, writes the command: */15 * * * * bash <full path to the script file> .

You can check running tasks using the crontab -l command .

Now our remote repository is updated every 15 minutes from the local one. Good luck!
 
