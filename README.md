# PLPBasicGitAssignment
- This guide provides a clear explanation of how to set up a Git repository, make changes, and push them to GitHub for version control.

  **Task 1: Repository Setup**

- Log in to your GitHub account.
- Click the green "New repository" button.
- Name your repository "PLPBasicGitAssignment".
- Check the box to "Initialize this repository with a README".
- Click "Create repository".

**Task 2: Local Setup**

- Create a new folder on your desktop or preferred location named "PLPBasicGitAssignment".
- Open your terminal or command prompt application.
- Use the cd command to navigate to your newly created folder. For example, if your folder is on the desktop, you might type cd Desktop/PLPBasicGitAssignment.

**Task 3: Git Initialization**

- In the terminal, type the following command and press enter:
  `git init`
- This creates a new Git repository in your local folder.

**Task 4 : Connecting to GitHub**

- In your terminal, locate the URL of your GitHub repository. It should look something like https://github.com/<username>/PLPBasicGitAssignment (replace <username> with your actual username).
- Type the following command in your terminal, replacing <repository-url> with the actual URL you copied:
  `git remote add origin <repository-url>`
- This links your local repository to the one on GitHub.

**Task 5: Making Changes**

## Create a File:

- Inside your local folder ("PLPBasicGitAssignment"), create a new text file using a text editor eg VsCode.
- Name it "hello.txt".
- Open the file and add a simple message like "Hello, this is my first Git repository!".
- Save the file.

## Committing Changes:

- In your terminal, type the following command to stage the changes (add the file to the next commit):
  `git add hello.txt`
- Type the following command to commit the changes:
  `git commit -m "Add hello.txt with a greeting"`

**Task 6: Pushing to GitHub**

- Type the following command to push your committed changes to the GitHub repository:
  `git push -u origin main`
- This command pushes the changes in your local "main" branch to the "main" branch on your GitHub repository.
- The -u flag sets the upstream branch, making future pushes easier.
