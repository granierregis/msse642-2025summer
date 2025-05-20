# ASSIGNMENT #1

## Objective
This week you will:  
1. Learn how git works
2. Create your own account in GitHub
3. Create a remote repo in GitHub
4. Create a local Repo on your Windows, MAC, or Linux system

## ACTIVITY 1: Research git

### Part 1
- Using your prefered research methodology (books, web seraches, ChatGPT), research how Git works at a high level. At a minimum
cover the following: 
    - Types of version control systems.  What type is Git?
    - Snapshots
    - What is a repository? Remote vs. local. 
    - What is commit?
    - What is working directory?
    - What is Staging Area
    - Find a good diagram that illustrates the architecture and the flow
- Take notes on this.  You will need it later.

### Part 2 
- If you are using Windows, install Git Bash (not necessary for Mac and Linux)
- Install Visual Studio Code

# ACTIVITY 2:  Setting up a new github and local repo

- Create a GitHub account if you don't already have one
- Create a rep for this class
- When you create the repo you will see instructions about how to set up your local repo.  Below is a slighly modified version of the 
instructions you will see.
- In a Bash shell (Git Bash for Windows or terminal for Mac or Linux) run the following commands.  
- NOTE:  you will be accessing the repo via HTTPS and you will be storing your configuration in your local repo, not globally.  This will make it easier to use multiple Git Hub accounts. 

```
echo "# msse642-2025summer" >> README.md
git init
git add README.md


git config --local user.email "rgranier@regis.edu"
git config --local user.name "Randall Granier"


git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/granierregis/msse642-2025summer.git
git push -u origin main
```

# ACTIVITY 3: Edit the README.md file and push to your GitHub Repo.  

- On your local machine, use an editor like Visual Studio Code to edit the README.md file you created in the previous Activity. 
- Add the results of the research in the first Activity. 
- push your edited file to your git hub repo.  

# WHAT TO TURN IN

- In the Slack channel #github-project, post the link to your GitHub repo that you created above.   
