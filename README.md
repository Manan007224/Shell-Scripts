These are all my scripts that I frequently use.

1. bkupro: Takes a backup of all '.\*' files from the /home/usr directory and copies it to /home/usr/Backup-profiles/ .

Usage: $bkupro

2. clnbkup: removes all files from the directory /home/usr/Backup-profiles.

Usage: $clnbkup

3. fastgit: Takes all files from the current directory and prompts user for a commit message, then pushes all the files to the git. A repository needs to be created in that directory for it to work.

Usage: $fastgit

4. initgit: initializes a repository at the current working directory and ask the user to put anything in the Readme.md, asks user to input the first commit message and asks the user whether they want to push the origin to a preexisting repo or not.

Usage: $initgit

5. prm: Permanantly removes all files that were temporarily moved to the directory /home/usr/Temp-Trash, asks users to confirm before deleting all files.

Usage: $prm

6. srm: Safely moves the files to /home/usr/Temp-Trash/ so that the user can review the files before actual deleting them completely.

Usage: $srm <file-1> <file-2> <file-3>... 

