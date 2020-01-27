## Memento git command

**If it's your first time to use Git, please follow instructions bellow** <br>

**I- The first part, you will have to do it only once.**

1- Fisrt step is to create an account in github 

2- Download git from URL:  https://git-scm.com/downloads

3- Open a new git bash and tap following command:

Create a directory 
```shell
  mkdir [name_directory]
```

Go to the directory you have just created 
```shell
  cd [name_directory]
```

Turn an existing directory into a git repository
```shell
  git init
```

Configure user information for your local repository (the email should be the same one you have registred with in github)
```shell
  git config --global user.name "Your Name"
  git config --global user.email you@example.com
```

Clone the project from this repository by using :
```shell
  git clone https://github.com/aminebennani25/CenseProject.git
```

Create a bridge between your local repository and the online one
```shell
  git remote add origin git@github.com:aminebennani25/CenseProject.git
```

You can verify your remote 
```shell
  git remote -v
 ```

**II- The second part should be done every time you want to commit your changes.**

Switch to the specified branch (Our work will be generally on branch-name:"Dev")
```shell
- git checkout <branch-name>
```

Verify in which branch you are and what are the new modification 
```shell
  git status
```

You can check the log also
```shell
  git log
```

Add the changes
```shell
- git add <file>
 ```
 
Commit your changes (The option is for adding a label to the commit)
```shell
  git commit <file> [option -m]
```

Updates your current local working branch with all new commits from the corresponding branch on GitHub
```shell
  git pull
```

Before push check if there are no conflicts otherwise they will have to be resolved. If it's OK, then push
```shell
  git push 
```

>**NB. For more information about git command line, browse the following link: https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf**<blockquote>
