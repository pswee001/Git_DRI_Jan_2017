## Setting up Your Remote Repo

Now, let's add this directory to GitHub so we can share it with others and start collaborating.

- Go to **GitHub** in your browser and click the plus sign in the upper right hand corner to create a new remote repo. 

- Give it the same name as your local repo. Skip the "add README.md" step, since you're importing an existing directory.

- Navigate to your new remote repo in the browser, and copy its HTTPS: URL. 

In the **command line**, check your git status

`git status`

and make sure all your commits are up to date. When they are, type

`git remote add origin [URL of your remote repo]` 

This will link the local and remote repo. To confirm, type:

`git remote -v`

If you're getting stuck, setting up a [remote repo in GitHub](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/) is a good resource.

---

[glossary](glossary.md) [helpful commands](helpfulcommands.md)