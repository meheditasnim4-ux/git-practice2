Objective:
The objective of this lab is to learn the basic workflow of Git and GitHub. It includes creating a GitHub repository, adding a C++ file, cloning the repository to the local computer, modifying the file, tracking changes using Git commands, committing the changes, and pushing the updated file back to GitHub.

Procedure:
Step 1: Create a GitHub Repository
At first, I installed Git Bash. Then I created a GitHub account and created a new repository. I named the repository git-practice, selected it as Public, and enabled the README file.

Step 2: Create the Initial File
I opened the repository and selected Add file → Create new file. I created a file named main.cpp, pasted the C++ code provided on the course portal, and clicked Commit changes.

Step 3: Clone the Repository
Next, I opened Command Prompt and cloned the repository using the following command:
git clone https://github.com/meheditasnim4-ux/git-practice.git
This downloaded the repository to my local computer.

Step 4: Open the Repository
I entered the repository folder by using the command:
cd git-practice

Step 5: Check Repository Status
I checked the repository status by running:
git status
The output was:
On branch main
nothing to commit, working tree clean

Step 6: Modify the File
I opened main.cpp in Code::Blocks and updated my personal information, including:
Name: Mehedi
Student ID: 24-57993-2
Section: M
Then I saved the file.

Step 7: View the Changes
I used the following command to view the modifications:
git diff
Then I checked the status again:
git status
The output showed:
modified: main.cpp

Step 8: Stage the Changes
I staged the modified file by using:
git add main.cpp
I also used:
git add .
Finally, I checked the status again using:
git status
The file appeared in green under Changes to be committed.

Step 9: Commit the Changes
Initially, I entered an incorrect command:
git commit-m "Updated student information"
After correcting it, I configured my Git username and email using:
git config --global user.name "meheditasnim4-ux"
git config --global user.email "meheditasnim4@gmail.com"
Then I committed the changes using:
git commit -m "Updated student information"

Step 10: Push the Changes
Finally, I uploaded the changes to GitHub by using:
git push
After refreshing the GitHub repository in the browser, the updated main.cpp file was successfully available online.

Outcome:
Successfully created a GitHub repository.
Created and committed a main.cpp file.
Learned how to clone a repository to a local computer.
Modified the source code locally.
Practiced Git commands such as git status, git diff, git add, git commit, and git push.
Successfully synchronized the local repository with the remote GitHub repository.

