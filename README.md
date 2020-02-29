# first-git

Trying to go through a github tutorial to test out how github works!
On my video with codetrain, I learned how I can create various branches.
Branches are like different versions of a doc (1st draft, 2nd draft, 3rd draft)
Each branch, we can commit and choose to merge to our master draft using a pull request
A pull request shows all the different changes in the commited branches
Backtracking, GitHub is a platform that hosts git which is a version control. Essentially,
GitHub stores the various changes of files and is great for collaborating.

A fork is used to create a duplicate of a repo from another account. Using forked repo,
users can create their own commits to the file and even send pull requests to the original
author/programmer. They can choose if they'll accept or not accept the pull request.
Users also have the option to leave comments to other users at the pull request page.

I created my own issue for coding train regarding his rainbow-poem. If they don't accept/deny
the request, then it will remain open. However, if they accept or deny it, it will be a closed
issue.

Now, I'm learning how to clone git repos & use my terminal to communicate with GitHub browser
and my laptop. Here's how it works:

git clone (insert repo URL)
git push (origin) (branch name) //Sends the local copy into github
git remote //Shows the "file location name" of the github repo (usually named origin)
git status //Shows the status of the local file (modified, not modified)
git commit -a -m "" //a = commits all new edits, m = comment for new edits
git log //Shows all the commits in a "log" format
git config --list //Shows all the configuration setting of github profile
git config --global user.mail //Ensures that when files are pushed, that it goes to the right account
git config --global user.name //Creates a github username in local directory

Process:

1. Make the edits to the local file
2. Save the local file
3. git commit
4. git push origin (branch name)
