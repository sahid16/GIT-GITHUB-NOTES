# creadit to hitesj choudry sir and chaidocs

## creating a repository 
 `git status` this command show you current status of your repository

 `git init` this command will ctreate a folder in your system name of `.git` for initialize it as git repository and .git folder is hidden

## commit
commit is a way to save your changes to your repository. It is a way to record your changes and make them permanent. You can think of a commit as a snapshot of your code at a particular point in time. When you commit your changes, you are telling git to save them in a permanent way. This way, you can always go back to that point in time and see what you changed.

## Complete git flow
`git init`==[working directory]--->`git add`==[staging area]--->`git commit`==[repo]--->`git push`==[github]

When you want to track a new folder, you first use init command to create a new repository. Then you can use add command to add the folder to the repository. After that you can use commit command to save the changes. Finally you can use push command to push the changes to github. Of course there is more to it but this is the basic flow.

## stage 
Stage is a way to tell git to track a particular file or folder. You can use the following command to stage a file:

`git init`
`git add <file> <file2>`
`git status`

Here we are initializing the repository and adding a file to the repository. Then we can see that the file is now being tracked by git. Currently our files are in staging area, this means that we have not yet committed the changes but are ready to be committed.

## commit 

`git commit -m "commit message"`
`git status`

Here we are committing the changes to the repository. We can see that the changes are now committed to the repository. The -m flag is used to add a message to the commit. This message is a short description of the changes that were made. You can use this message to remember what the changes were. Missing the -m flag will result in an action that opens your default settings editor, which is usually VIM. We will change this to vscode in the next section.

## logs

`git log`
This command will show you the history of your repository. It will show you all the commits that were made to the repository. You can use the --oneline flag to show only the commit message. This will make the output more compact and easier to read. 

Atomic commits are a way to make sure that each commit is a self-contained unit of work. This means that if one commit fails, you can always go back to a previous commit and fix the issue. This is important for maintaining a clean and organized history in your repository.

## gitignore
Gitignore is a file that tells git which files and folders to ignore. It is a way to prevent git from tracking certain files or folders. You can create a gitignore file and add list of files and folders to ignore by using the following command:
`.gitignore`
   file1
   file2
   file3
Now, when you run the file1, it will not show the file2 and .file3 as being tracked by git.

## Conclusion
In this section, we have learned about the basics of git and how to use it to track changes to your files and folders. We have also learned about the different commands that you can use to interact with your repository, such as init, add, commit, log, etc By the end of this section, you should have a good understanding of how to use git and how to use it effectively to manage your code.