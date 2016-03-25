#GitHub for Dummies
This is a simple tutorial on GitHub. You have tonnes of stuff and tutorials on git and gitHub. This is my version of it.

###About GitHub Project...
A Project in github is referenced by the user it is hosted by along with the repository it is hosted in. A project hosted by tinut in GitHubTutorial will reside at https://github.com/tinut/GitHubTutorial. First step to collaborate with a project is to find the GitHub copy of the project. This might require permissions from repo owners.

Once you have found the repository which you want to collaborate, you can fork the github project on to your account using fork button. This creates a repository of same name under your username. You may not have permissions to fork a private repo.


Another thing you could do is clone the project into your local system. For the purpose of this tutorial, you can clone GitHubTutorial project.

```
cd /Projects/GitHub/
git clone https://github.com/tinut/GitHubTutorial
```

You could make changes to the clones file as per your liking. After changing into cloned directory, let us add a new file. Replace <myfile>.java with any name of your choice. 
```
cd GitHubTutorial/
touch <myFile>.java
echo "Hello GitHub" >> <myFile>.java
```
Now, the file contains the text 'Hello GitHub'. 'Hello GitHub' is by no means a valid java syntax. But, we know that you are good at Java. Say, you took 3-4 days, but still have managed to carve out a beautiful java class in the same file that can do some magic in coding world. You want this beauty to be seen by the world. You want it to be pushed back to gitHub. How would you do it?

Now, First step to push a change is to add the files to the staging. We should express our desire to commit any changes  by adding the changes to staging phase. This is like telling git that we are interested in committing.
```
git add <myFile>.java
```

Once you have staged the changes, you could commit the changes. This is equivalent to group a set of staged changes and assigning it an revision ID and name. This revision ID can be used in future to reference all the changes committed. A set of changes in commited order is called commit history or revision history.
```
git commit -m "Message for commit"
```

