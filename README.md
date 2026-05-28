# Practice-Git-and-Github
# Installation

1. Download the latest version from [git](https://git-scm.com).
2. Git installation [Video](https://www.youtube.com/watch?v=Kx1titsO57Q).
3. After installation, open Git Bash or Command Prompt and run: `git --version`
4. Create Acount and login.

# Configration Levels 
Command use in git terminal
Git stores settings in three different locations depending on the desired scope:

- **System**   `--system`  For all users on the computer.
- **Global**   `--global`  Specific to you as a user.
- **Local**    `--local`   Specific to one repository (default).

# Configration Git
1. Set Username
`git config --global user.name "Your Name"`
2. Set Email
`git config -- global user.email "Yourmail@gnail.com"`
3. check Configuration
`git config --list`
4. Set Vs code as Default Editor
`git config --global core.editor "code --wait"`

- Extra Configuration
`git config --global core.autocrlf ture`
`git config --global core.autocrlf input`
`git config --global core.autocrlf false`
`git config --global -e`

# Clone And Status 
command use in vs code terminal
- Clone: Cloning a repository on our local machine
    `git clone <- some link ->`
- Status: Displays the state of the code
    `git status`

- Untracked: new file that git doesn't yet track
    Untracked files:
  (use "git add <file>..." to include in what will be committed)

- Modified: changed 
    Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
- Staged: file is ready to be commited
- Unmodified: unchanged 

# Add And Commit
- Add: adds new or changed files in your working directory to the git staging area.
    `git add <- file name ->`

- commit: it is the record of change
    `git commit -m "some message"`

# Push command 
- Push: upload local repo content to remote repo
    `git push origin main`



