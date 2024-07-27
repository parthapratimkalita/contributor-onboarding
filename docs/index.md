# Basic Tutorial for Open Source Development on GitHub

## Legend
Sections marked with an asterix (*) are meant to be executed only by the team leader. These sections typically involve 
one-time tasks, such as setting up a branch protection rule. 

## Requirements

### Required
- A [Github account](https://github.com/join).
- [Git](https://git-scm.com/downloads) installed on your computer.
- [Python3](https://www.python.org/downloads/) installed on your computer

### Recommended:
- [GitHub Desktop](https://desktop.github.com/download/) installed on your computer
- [Pycharm Community Edition](https://www.jetbrains.com/pycharm/download/other.html]) installed on your computer

## *Forking a Repository

1. Go to the repository you want to fork: https://github.com/AutoResearch/contributor-onboarding
2. Click the "Fork" button in the upper right corner of the page.
3. Select your username as the destination for the fork.
4. You may add a description to the fork if you wish.
5. Check the box "Copy the ``main`` branch only".
6. Click the "Create Fork" button.
4. You now have a copy of the repository in your account.

### Enable Issues
1. Go to the repository on GitHub you just forked.
2. Click the "Settings" tab.
3. Scroll down to the "Features" section.
4. Check the box "Issues".

## *Adding Contributors to a Repository
1. Go to the repository on GitHub you want to add contributors to. This is the repository you just forked.
2. Click the "Settings" tab.
3. Click the "Manage access" button.
4. Click the "Invite a collaborator" button.
5. Enter the username of the person you want to add as a contributor.
6. Note: For this exercise, you will want to give the person "Maintain" access.
6. Click the "Add [username] to this repository" button.
7. The person you added will receive an email invitation to contribute to the repository.
8. Once they accept the invitation, they will be able to contribute to the repository.

*Hint: You can also add contributors by adding their GitHub username to the `CONTRIBUTORS.md` file in the repository.*

## *Adding Branch Protection Rules
1. Go to the repository on GitHub you want to add branch protection rules to. This is the repository you just forked.
2. Click the "Settings" tab.
3. Click the "Branches" tab.
4. Click the "Add classic branch protection rule" link.
5. Enter the name of the branch you want to protect. For this exercise, you will want to protect the ``main`` branch.
6. Check the box "Require pull request reviews before merging".
7. Check the box "Require approvals".
8. Enter the number of approvals required. For this exercise, you will want to require two approvals.
7. 


## Cloning a Repository

### Cloning with GitHub Desktop

*Note: You may have to log into your GitHub account from GitHub Desktop before you can clone a repository. 
You may also need to give GitHub Desktop permission to access your GitHub account.* 

1. Open GitHub Desktop.
2. Click the "File" menu and select "Clone Repository".
3. Select the "URL" tab.
4. Paste the URL of the repository you want to clone.
5. Choose a local path for the repository.
6. Click the "Clone" button.
7. You now have a copy of the repository on your computer.

### Cloning with git
1. Open a terminal.
2. Navigate to the directory where you want to clone the repository.
3. Run the following command:
```bash
git clone repository_url
```
4. You now have a copy of the repository on your computer.



