# Gethub Forking
Overall workflow:
- Fork a repo
- Clone a forked repo locally
- Create a branch
- Add and commit changes
- Push changes
- Open a pull request

### Step 1: Open the Terminal and authenticate using gh (Github CLI): 
gh auth login

### Step 2: Create an authentication token in your Github account with specified scopes given in the terminal. Copy it from Github and paste it. Verify authorization was successful.

### Step 3: Visit the target repo and click the fork button. 
A Create a new fork view will appear. Select the dropdown for the owner to the account you want to fork to. Keep the default name and then click on the Create Fork button. 

### Step 4: Clone the forked repository using the GitHub CLI command. 
gh repo clone <YOUR USERNAME>/<REPOSITORY-NAME> 

### Step 5: Move to the repo directory by using cd <REPOSITORY-NAME>

### Step 6: Create and checkout a new branch.
git checkout -b my-branch 

## Step 7: Make all the changes you need

### Step 8: Add your changes
git add class.md 


### Step 9: Commit your changes with a message using the -m flag
git commit -m 'minor changes'

### Step 10: Push your changes to your fork
git push origin my-branch 

### Step 11: Visit the class repo and click Pull Requests.

### Step 12: Click on New Pull Request.

### Step 13: On the compare page click "compare across forks"

### Step 14: Select the main branch as "base"

### Step 15: Select your fork and the committed branch (my-branch) as "fork" and then click on the "Create pull request"

### Step 16: Give your pull request a title and description

### Step 17: Click "Create Pull Request" button to initiate your pull request.

### Step 18: Once your pull request is complete copy the pull request ID from the title or the URL. 

















