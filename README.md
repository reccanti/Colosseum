#Colosseum
Colosseum is a game, made with RPG Maker MV, in which a player creates a team to fight against monsters. 

#Setup
This repo does not keep track of any of the art or sound assets, so it won't be as simple as cloning it. To get it set up, you'll have to create a new RPG Maker project and pull the data files into it.

##Step 1 - Create a Project
In RPG Maker MV, create a new project in the directory of your choice

##Step 2 - Create a git repository
In your terminal, go to that directory and initialize a git repository

```
cd PATH/TO/YOUR/DIRECTORY
git init
```

##Step 3 - Add this repository as a remote
You'll need to get a reference to this repository in order to get the files

```
git remote add origin https://github.com/reccanti/Colosseum.git
```

##Step 4 - Fetch the files and overwrite the defaults
Now that we have a reference to this repository, we can overwrite our base files with the current master branch

```
git fetch --all
git reset --hard origin/master
```

And with that, you should be good to go!