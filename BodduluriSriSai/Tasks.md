CODEWAYY TASKS
==============
Task 1
-------
1. Git is a software which keeps the track of the projects that we have done on our computer whereas GitHub is a webservice where we can do all git things.
2. GitHub is an open source platform where a large number of programmers  can  store ,update there projects based on there versions.
3. version control system means where we can store the project any number of times whenever we commit where we can also access the previous version.git is a distributed version control system which has local repository and can be accessed from anywhere.
4. other platforms are:
  Gitlab,bitbucket,gitbucket,cloud source           repository .....
5. Every month I do a lot of projects where I use to start again from first whenever I got an error so git and GitHub are very helpful to check in which version I am wrong and to continue from my previous version.

Task 2
--------
1. How git workflows works?
Ans.There are three main components of a Git workflow :
    * Repository : The repository, or repo, is the “container” that tracks the changes to your ]project   files. It holds all the commits—a snapshot of all your files at a point in time—that have been made.
      You can access the commit history with the Git log.
    * Working tree : The working tree, or working directory, consists of files that you are currently working on.
      You can think of a working tree as a file system where you can view and modify files.
    * Index : The index, or staging area, is where commits are prepared. The index compares the files in the
      working tree to the files in the repo. When you make a change in the working tree, the index marks the file
      as modified before it is committed.

2. What are the different stages of a git project as a commit, add?
Ans. 
    * Untracked: the file exists, but is not part of git's version control
    * Staged: the file has been added to git's version control but changes have not been committed
    * Committed: the change has been committed

3. Is it possible to do a git commit before git add,  if you made any changes. Explain why?
Ans.No, because you have to explicitly tell Git which changes you want to include in a commit
    before running the "git commit" command. This means that a file won't be automatically    included  in the next commit just because it was changed. Instead, you need to use the "git add" command  to mark the desired changes for inclusion.

4. Why is git diff used ?
Ans.The diff command calculates and displays the differences between two files, and is typically used to investigate the changes between two versions of the same file.Compares the working directory with index, i.e. shows the changes that are not staged yet.

5. Can we leave the commit message as blank?
Ans.Yes, git generally requires a non-empty message because providing a meaningful commit message is part
    of good development practice and good repository stewardship. The first line of the commit message is
    used all over the place within git.

# Link to github repository:

https://github.com/boddulurisrisai/git_series

Task 3
-------
1. What is meant by the term fork and clone?
Ans.
 * The term fork means producing a personal copy of someone else project.Git Fork means
      you just create a copy of the main repository of a project source code to your own GitHub profile.
 * The term clone means getting a local copy of the code present in the repository. After cloning    you  can then do whatever changes you like in the code and then you can pull the changes back to the repository.

2. What are branches in Github?
AnsBranches are the feature used for separating a feature or part of code from  master in order
    not to mess something in your main code.We can create,rename,update,delete branches and can
    merge with th master branch if required.

3. What is PR?
Ans.PR means Pull requests in which u tell others about changes you've pushed to a GitHub repository.
     Once a pull request is sent,interested parties can review the set of changes, discuss potential
     modifications, and even push follow-up commits if necessary.

4. Can we delete the master branch if not Why?
Ans.Yes,we can delete the master branch using git commands first i local repository and then remote repository.
   * First you delete master in your local clone. To do this we first make a new branch called placeholder
     or similar, and delete master from there:
     git branch placeholder
     git checkout placeholder
     git branch -D master
   * Next we must delete the branch on github
     git push origin :master

5. How can we delete a branch? (Explore a bit about this yourself)
Ans.Deleting a branch locally
    *  Git will not let you delete the branch you are currently on so you must make sure to checkout a     branch that you are not deleting. For example: git checkout master
      git branch -d <branch>
   * deleting a branch remotely
     git push <remote> --delete <branch>
               or
     git push <remote> :<branch>

# PR links:

* https://github.com/codewayy/github_series/pull/71

* https://github.com/codewayy/github_series/pull/1

