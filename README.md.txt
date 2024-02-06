Step 1: Initialize Git Repository
bash
Copy code
git init
Step 2: Stage Changes
bash
Copy code
git add .  # Or specify files instead of dot if needed
Step 3: Commit Changes
bash
Copy code
git commit -m "Initial commit"
Alternatively, you can combine staging and committing:

bash
Copy code
git commit -am "Initial commit"
Step 4: Create a Repository on GitHub
Go to your GitHub account.
Create a new repository.
Select the desired options and files.
Step 5: Connect Local Repository to GitHub
bash
Copy code
git remote add origin 'Your GitHub Repo URL'
Step 6: Rename the Branch to 'main'
bash
Copy code
git branch -M main
Step 7: Push Changes to GitHub
bash
Copy code
git push -u origin main
Step 8: Enter GitHub Credentials
You'll be prompted to enter your GitHub username and password.