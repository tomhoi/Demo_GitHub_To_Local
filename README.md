# Demo_GitHub_To_Local

## Link to video:
[link](https://www.youtube.com/watch?v=RGOj5yH7evk)

## One important comment in the video:

Here are some corrections to get the course right:

- When first opening the terminal in VS Code,  on the top-right of the terminal bar just change from "Powershell" to "Git Bash" and then follow along
Note: [link to change to "Git Bash" terminal in VS Code](https://neutrondev.com/vs-code-integrate-git-bash-default-terminal/)

- dont use SSH link when cloning...use HTTPS link so it becomes "git clone xxxHTTPSxxx"

- dont use "git push origin master" --> use "git push origin main" 
 because the naming convention has changed from master to main
 
## On GitHub

### Step 1
Create a repository on GitHub. 
Add README.md for testing purpose

### Step 2
Edit README.md

## Locally

### Step 1

- Use VS Code to open a folder of choice
- Change terminal to "Git Bash"

### Step 2

`git clone https://github.com/tomhoi/Demo_GitHub_To_Local.git`

## Continue your work locally

### Step 1
Add files ...

### Step 2
- `git status`
- `git add .`
- git commit -m "some message"`
- `git push -u origin master`





