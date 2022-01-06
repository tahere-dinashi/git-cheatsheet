# git-cheatsheet
This Repository is include some question and answers about git and git commands for devops class.[dws-dev-005-git.pdf](https://github.com/tahere-dinashi/git-cheatsheet/files/7775622/dws-dev-005-git.pdf)

@dwsclass
#bloodrina group
#dws-dev-005-git
------
A number of git commands: 
If you want to get a copy of an existing Git repository — for example, a project you’d like to
contribute to — the command you need is git clone.
#git clone <url>
------
If your current branch is set up to track a remote branch, you can use the git pull command to automatically fetch and then merge that
remote branch into your current branch.
#git pull 
------
When you have your project at a point that you want to share, you have to push it upstream. The
command for this is simple:
   #git push <remote> <branch>.
If you want to push your master branch to your origin server (again, cloning generally sets up both of those names for you automatically),
then you can run this to push any commits you’ve done back up to the server:
  # git push origin master
------
After you have created several commits, or if you have cloned a repository with an existing commit
history, you’ll probably want to look back to see what has happened. The most basic and powerful
tool to do this is the git log command.
  #git log
------
If the git status command is too vague for you — you want to know exactly what you changed, not
just which files were changed — you can use the git diff command.
  #git diff
------
Like most VCSs, Git has the ability to tag specific points in a repository’s history as being important.
Typically, people use this functionality to mark release points.Git supports two types of tags: lightweight and annotated.
  #git tag -a <v1.4 -m "my version 1.4">
------
If you want to view the versions of files a tag is pointing to, you can do a git checkout of that tag, for example: 
  # git checkout v2.0.0
------
If moving the branch pointers around isn’t going to work for you, Git gives you the option of
making a new commit which undoes all the changes from an existing one. Git calls this operation a
“revert”
  # git revert 
------
git-reset - Reset current HEAD to the specified state
  #git reset
------
git-merge - Join two or more development histories together
  #git merge
------
git-rebase - Reapply commits on top of another base tip
  #git rebase 
