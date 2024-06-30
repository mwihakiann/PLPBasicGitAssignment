# PLPBasicGitAssignment
All about Git.
Here are the detailed steps for each task:

### Task 1: Repository Setup

1. GitHub Repository Creation:
   - Log in to your GitHub account.
   - Click on the "New repository" button or navigate to https://github.com/new.
   - Fill in the repository name as "PLPBasicGitAssignment".
   - Optionally, add a description.
   - Check the box to initialize the repository with a README file.
   - Click on the "Create repository" button.

### Task 2: Local Setup

2. Local Folder Setup:
   - Create a new folder on your local machine, named "PLPBasicGitAssignment".
   - Open a terminal or command prompt and navigate to the created folder:
     sh
     cd path/to/PLPBasicGitAssignment
     

3. *Git Initialization:*
   - Initialize a new Git repository in your local folder:
     sh
     git init
     

4. connecting to GitHub:
   - Link your local repository to the GitHub repository you created in Task 1. Replace <repository-url> with your actual repository URL:
     sh
     git remote add origin https://github.com/yourusername/PLPBasicGitAssignment.git
     

### Task 3: Making Changes

5. Create a File:
   - Inside your local folder, create a new text file named hello.txt.
   - Add a simple text message (e.g., "Hello, Git!") to the file.
   to create a file use touch "file name"
   to add text message echo "text message" > file name

6. Committing Changes:
   - Stage the changes:
     sh
     git add hello.txt
     
   - Commit the changes:
     sh
     git commit -m "Add hello.txt with a greeting"
     

### Task 4: Pushing to GitHub

7. Pushing to GitHub:
   - Push the committed changes to your GitHub repository:
     sh
     git push -u origin main
     

### Task 5: Verification

8. *Verify on GitHub:*
   - Visit your GitHub repository in a web browser and confirm that the hello.txt file and commit message are visible.

