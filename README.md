# Git Workshop
A git workshop covering some basic git features with a trunk based branching strategy.

## Getting Started

To follow along all you will need is:
- An IDE or text editor
- A Git client or terminal environment
- A Github account

### Creating your own copy of this repository

Start by logging into your github account, and forking [this](https://github.com/gtugwell/git-workshop) repository. This will create a repository in your github account so that you can follow along.

Once you have created the fork, you can now clone the repository to your system. Follow Github's instructions on cloning a repository [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).

Now that you have this repository cloned locally, you can start to create your own branches and practice branching and merging code!

### Creating your first branch

If you are following along using a Git Client, perform the following steps using the client instead of the command line.

Open your terminal, and navigate to the folder where you cloned this repository.

Once inside, type `git status` to check and make sure you are in the right folder. If you are in the right folder, you will see what branch you are on. If you aren't you will likely see an error. This means you are not yet in the correct folder.

To create your first branch, type `git checkout -b feature/my-first-branch`. This will create your new branch locally.

From here, we can modify our code:

# code modifications here

Then, once we are finished, we can add all of our changes with `git add .` which will add all modified files. Be care using the `.` in the future because this will add ALL files you modified, which might not always be your intention.

Now you are ready to commit your changes. Try something like `git commit -m "My first commit."`. The part following the `-m` flag in quotes will be the commit message that shows up in your repository commit log.

Finally, you can push your code with `git push`. You may have to do an additional step that the terminal prompts you to do. Once you do that, you should now see that new branch reflected in your Github repository.

### Creating your first pull request

In your Github repository, you should see a tab at the top that says 'Pull requests'. Click that tab.

Click on the green button on the right side of your screen that says 'New pull request'. From here you can choose which branches we are creating our pull requests on, in this case we are merging our new branch `feature/my-first-branch` into our `main` branch.

Once we create that pull request (also known as a 'PR'), we can review our changes, and complete it!

Once we have completed it, our changes we made in `feature/my-first-branch` will now show up in our `main` branch.

