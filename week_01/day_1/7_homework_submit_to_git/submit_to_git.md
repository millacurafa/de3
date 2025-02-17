Submitting Files to Git
=======================

We’ve walked through the steps required to add and commit files locally,
then add them to a github repository. Now it’s time for you to try it
yourself! Follow the steps below to create files, track them and push
them to a remote repository.

MVP
---

We want to create a homework directory structure and repo similar to the
classnotes repo you cloned earlier.

Remember, in everything that follows, **never create a repo (`git init`)
or clone (`git clone`) inside an existing repo**. So, if you see
`git:(master)` at the start of your command prompt, don’t `git init` or
`git clone` in that location, as you are inside an existing repo!

Working locally on your own computer:

-   Create a folder in the directory where you’re keeping your work
    files. Call it `codeclan_homework_yourname` (insert your name as
    something like `DelMiddlemiss`).
-   Initialise a Git repository in the folder
-   Create a `week_01` folder and `cd` into it, then create a `day_1`
    folder and `cd` into that.
-   Create a couple of `.txt` files in the folder
-   Stage the files
-   Commit the files
-   Make a change to each file
-   Commit the changes

Working remotely at [GitHub](https://github.com/):

-   Create a new repository – call it `codeclan_homework_yourname`
    (again, insert your name as something like `DelMiddlemiss`)

Back on your computer:

-   Add the GitHub remote to your local
-   Push to the remote repository

Extension
---------

Investigate how to ignore files when working with Git. You can find the
official documentation [here](https://git-scm.com/docs/gitignore), but
there are lots of resources available which are more
[user-friendly](https://medium.com/@haydar_ai/learning-how-to-git-ignoring-files-and-folders-using-gitignore-177556afdbe3).
This can be useful you want to hide things like login credentials or
local configuration details from public view. When you’ve read the
documentation:

-   Create a `.gitignore` file
-   Tell it to ignore a file called `file_to_ignore.txt`
-   Stage it, commit it and push it to the remote
-   Create `file_to_ignore.txt`
-   Add some text to it
-   Use `git status` to check that `file_to_ignore.txt` isn’t being
    tracked by Git

If you’ve set up `.gitignore` properly you should be able to do whetever
you like to `file_to_ignore.txt` without Git caring!

Remember that this is an **optional** extension to the homework. In labs
and homeworks the important concepts are covered in the **MVP** section
– if you can complete that then you’re doing fine. If you want to push
yourself further then have a go at the extensions, but they’re not
essential!
