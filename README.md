# Github-Workshop
Repo for 2018 Fall Github-Workshop
9/30/18

# Workshop Goals
The goal of this workshop is to provide a baseline familiarity with using git + GitHub. At the end of this workshop, you should be able to 
- Clone a repo
- Create a branch
- Commit changes
- Create a pull request
- Approve a pull request
- Land your changes

Essentially, the basic functionalities of a GitHub-based development pipeline.

# Instructions:
0. Ensure you are a colaborator on this repo! Talk to your PM if you are not, and they will add you. 

1. Clone this repo: 
`git clone https://github.com/JumboCode/GitHub-Workshop.git`

2. Create a new branch. Label it with your name and the feature:
`git branch [first name]-[last name]/workshop`
e.g. `git branch tony-monaco/workshop`

When making branches, it's important that their names correlate directly to their new feature. In an actual repo, this might be something like `ton-manaco/header-bar-styling`

3. Ensure your branch was created by running `git branch`. This will list your branches, you should see something like:
```
$ git branch
$ * master
$ tony-manaco/workshop
```

4. Check out your branch. This ensures change you make will be added to that branch only. 
`git checkout [first name]-[last name]/workshop`

5. Ensure you are on the right branch, again by running `git branch`. a `*` will be in front of your current branch, like:
```
$ git branch
$ master
$ * tony-manaco/workshop
```

6. Add a new file to this directory! Create a new file, call it `[first name]-[last name].txt`. Put whatever you want in the body of the file.

7. Run `git status`. You should see something like:
```
On branch tony-monaco/workshop
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	tony-monaco.txt

nothing added to commit but untracked files present (use "git add" to track)
```

8. Follow those git status instructios-- run `git add [file]`, e.g. `git add tony-manaco.txt`
