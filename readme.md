# Git Crash Course
Git is a tool that you can use to collaborate with your team members ya know. 
Imagine you and a friend are working on the same project. Hmm, what happens
when both of you need to make seperate changes? What if those changes happen
to the same file?

Git is a version control system. It will help manage your project over time
and handle multiple collaborators. *I started this repository so you can
practice collaborating with others.*

## Get Access
Slack me your @ name or follow me on github and I'll give you access to make
changes to the repository.

-----

## Clone this Repository
My code is hosted on github's servers. Copy it onto your local machine.
```
cd ~/my/deploy/directory
git clone https://github.com/kjpark/collabo.git
```

## What's going on?
```docker-compose up```

LOOK HOW EASY THAT WAS!!... and navigate to `'0.0.0.0:5000'`. You should see a website. Play around with
the code and try to add yourself to the directory.

## Ok GO
First, check to see what changes git has detected.

```git status```

Then add whatever changes you made to the stage.

```git add whateverfiles```

Check to make sure you're ready to commit (save) by running `git status` again
and then commit if everything looks good.

```git commit -m "a nice, descriptive message"```

And finally, send your changes back to the remote github repo.

```git push```

And if/when you need to grab changes that a teammate made / update to the
latest codebase:

```git pull # which just runs git fetch followed by git merge```