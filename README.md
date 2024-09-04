# Learn Git

**Git** is a tool for managing changes to your project. If there are going to be lots of developers all working on the same thing, having control of those changes is going to be important.

Everything that you do in Git revolves around four main concepts:

- Branches
- Commits
- The working directory
- The .git repository

### 1. First commit

Let's make a start by initializing a repository and add an initial commit to it.

Initialize a git repo
```git init```

Add changes to the staging area
```git add <filename>```
or
```git add .``` to add all changes

Commit changes to the repository
```git commit -m 'your messsage goes here'```

### 2. Git log

You can use git log to examine your history of commits.
```git log```

### 3. Branches

**Branches** are an important concept in Git and in version control in general. They allow you to create changes in isolation. You only merge them into the rest of the code when you are happy with them.

Here is an example of creating a second branch off of the master branch...

- List branches
```git branch```

- Create a new branch
```git branch <branch-name>```

- Change to another branch
```git checkout <branch-name>```

### 4. Merging Branches

Once you are happy with your changes, you can merge them into the master branch.
```git merge <branch-name>```

### 5.Git Switch

**git switch** is an alternative way to change to another branch

Switch branches
```git switch <branch-name>```

Create a branch and check it out with one command
```git checkout -b <branch-name>```
