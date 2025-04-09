So one of the simplest things that you can do with git on your machine, is that you can clone a repository to it. How do you complete this task? Either set up a repository online at github, or install extensions for github, or even download the git desktop app.
In this case, i will have already made a repository online. Now, github will have a screen that sayas "Quick Setup" and gives instructions on how to set up in your local machine quickly. Or you can use the command lines. I will use git clone, and clone my repository
by calling:
git clone https://github.com/gfiedler2026/newSkill.git 
you would obviously insert your own repo here.

Now, since my repo is empty it would display a warning that i'm cloning an empty repo. But this README will be my first "push" to my repo. I would accomplish adding a commit first, then calling git push.
git commit -m "adding README.txt file"
git push