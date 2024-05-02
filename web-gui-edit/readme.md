Press period in your repo to open up web gui codebases.

-> use source control menu in the left panel to see changes. add them to staged changes while commiting just for them. all otherwise.

## TESTING SH
```sh
test of markdown writing style ->  press altgr and comma on keyboard to write backticks. 3 backticks open markdown container
```


## TMP Folder Creation
```sh
cd ..
mkdir tmp
git clone https://github.com/idincern/GithubFoundationsTraining.git
cd GithubFoundationsTraining/
ls -la # to see hidden files in the folder. there is a .git folder in our ws which means that it is a git repo.
```

To initialize a git repo, type
```sh
git init
```

Type ``git status`` to see the git repo and staged changes.
type ``git add .`` to add all changes to staged. Otherwise, write name of the file to add them to the staged changes. If any error occurs, you can reset changes added to the staged changes by using ``git reset``.

To remove git repo(git folder): ``rm -rf .git``

```sh
git commit -m "Add commit message" #To add a commmit to the staged changes
```

```sh
git log # shows recent commits to the git tree
```

## .gitconfig file
To see the .gitconfig file, type:

```sh
git config --list
```

In the setup stage of git, we must define the global username and email to use the git.
you can set the username and email via:

```sh
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

## Opened github repo in local computer
Open test OK
