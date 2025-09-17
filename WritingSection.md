/* Which tool would you use for sharing this information with the instructor ? (shared google docs.. pdf… a simple file in your github repo? Anything works! )
ans: GitHub repo

Why Git forces you to pull before pushing.
ans: To merge in all the changes. 


Can you explain in your own words what caused the conflict, what the markers meant, which version you chose (and why), and how you confirmed the result was clean and pushed.
ans: The code difference between the local and GitHub repo caused the conflict. The markers meant to show the difference between the code of the local, incoming changes and the code existing in GitHub repo. We chose the code that was more readable.


Q1. You are working on a project and have some changes. How do you bring your uncommitted changes to a new branch? The command you should run is: _
ans: git checkout -b <branch name>

 Q2. When remote repository has some changes that your local machine doesn’t have, the command to apply the remote changes to your local repository you should run is: 
ans: git pull

Q3. In git VCS, the code can be in three “areas”: working directory, _________, and git directory. (This is the area the file changes would be in after you run the command git add <file-name>.) 
ans: Staging area

Q4 : What was the intent of the authors ?

git pull origin main
git checkout -b bugfix/missing-button
Intent: update the code to most recent and create a new branch named bugfix/missing-button.

git add button.js
git commit -m "Fix missing submit button on login page"
Intent: put button.js to staging and put the staging files into git repository.
 
git checkout main
git pull origin main
git merge bugfix/missing-button --no-ff
Intent: go to main branch, retrieve the most recent code, and then merge the bugfix/missing-button branch to main branch.

git push origin main
Intent: update the remote repository with the local version. */