# DATA601-Intro-To-Data-Science-Project - Statistical Analysis and Comparison of Classification Models for Credit Card Fraud Detection on an Imbalanced Dataset Using Wilcoxon Signed-Rank and Friedman Hypothesis Tests

Brief Git Tutorial and Environment Setup for Group Members:
1. Register/Login to github and access the HTTPS repo: https://github.com/mhan44/DATA604-Data-Management-Project. I will add you as a collaborator once you message me your username
2. Install git on your device from https://git-scm.com/install/ depending on your OS
3. (Optional) Install VSCode https://code.visualstudio.com/ and the relevant extensions: Jupyter, Jupyter Cell Tags, Jupyter Keymap, Jupyter Notebook Renders, Jupyter Slide Show, Markdown All in One, Markdown PDF, Markdown Preview Enhanced, Python, Python Debugger, Python Enviroments GitHub Pull Requests
4. In your device's terminal, cmd for windows, or the terminal in vscode, configure your git identity with these commands:
   * git config --global user.name "YOUR_NAME"
     * Not your github username, just a display name that can be anything
   * git config --global user.email "YOUR_EMAIL@example.com"
   * git config --global --list
     * To verify
   * You'll be asked to log in on first push/pull. For GitHub, you may need a Personal Access Token (PAT) instead of your password: GitHub → Settings → Developer settings → Personal access tokens → Fine-grained or classic → scopes: repo
   * The above PAT step can be skipped if you login to GitHub Pull Requests in Visual Studio Code
5. In VSCode or cmd, cd to your desired directory to copy the current working repository, for example:
   *  cd C:\Users\MyUser\Desktop\DATA601
6. Now in your desired directory, clone the repository:
   * git clone https://github.com/mhan44/DATA604-Data-Management-Project
   * cd DATA604-Data-Management-Project
   * Now you have copied the repository to your device and can commit/push changes. Your file path should look something like C:\Users\MyUser\Desktop\DATA601\DATA604-Data-Management-Project
7. GitHub automatically blocks any files larger than 100MB that are pushed to a repository via command line, like our dataset creditcard.csv. To bypass this, we install Git Large File Storage (Git LFS) like so:
   *  Make sure you are in the project directory: cd C:\Users\MyUser\Desktop\DATA601\DATA604-Data-Management-Project
   *  git lfs install
   *  git lfs pull
8. Editing, committing, and pushing
   * git status
     * After making edits to the Jupyter Notebook or documents in the repository, git status will show which files were modified, deleted, or are new in your local repository
   * git add <filename> <filename2>
     * To make sure that your local changes to any files are represented in the repository, you use git add to add the files that you modified to stage a commit
   * git commit -m "Commit message that briefly lists what changes were made any why, e.g. README Update for Tutorial"
     * After adding all the files you've modified, git commit will finalize those changes and attach a comment of your documentation
   * git push
     * Finally, git push will push your local commit to the main branch, where all of us can then git pull those changes and in practice, simultaneously work on the same document efficiently  
9.  Keeping up to date with updates - before starting any work, you should:
    * git checkout
    * git pull