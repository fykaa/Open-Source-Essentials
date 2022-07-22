# Open-Source-Essentials
Your Practical Guide to making Open Source Contributions! [![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)

<h1>Making Pull Requests</h1>
<p>Pull requests are the way we contribute to group projects or open source projects</p>

<h2> Step towards your First Pull Request! </h2>
<ul><li> Open https://github.com/fykaa/Open-Source-Essentials in a new tab </li></ul>
<ul><li> Make a change! Add your name in the above repository's <code>Contributors.md</code> file in order to make your first pull</li></ul>

## Create a folder in your computer

<ul><li>Right click to Open Git Bash Here</li></ul>

<ul><li>Create a Git repository on GitHub</li></ul>

<ul><li>Run following command on gitbash</li></ul>

     git init
     
<ul><li>Fork the repository you created on github</li></ul>
<ul><li>Clone your forked repository of the project </li></ul>

     git clone https://github.com/<your_username>/repository_name.git
     
<ul><li>Navigate to the project directory</li></ul>
<ul><li>Add a reference(remote) to the original repository</li></ul>

     git remote add upstream https://github.com/repository_owner/repository_name.git
     
<ul><li>Check the remotes for this repository</li></ul>

      git remote -v
     
<ul><li>Always take a pull from the upstream repository to your main branch to keep it updated as per the main project repository</li></ul>

     git pull upstream main
     
<ul><li>Create a new branch (prefer a branch name that relates to your assigned issue</li></ul>
     
     git checkout -b <YOUR_BRANCH_NAME>
     
   <ul><li>Perform your desired changes to the code base </li></ul>
   
   
   
  ### Check your changes
     git status
     git diff
  ### Stage your changes
     git add . <\files_that_you_made_changes>
  ### Commit your changes.
     git commit -m "relavant message"
  ### Push the committed changes in your feature branch to your remote repository
     git push -u origin <your_branch_name>
     
  ### To create a pull request, click on <code>compare and pull requests</code>
  ### Add an appropriate title and description to your PR explaining your changes.
  ### Click on <code>Create pull request</code>*9


 Congratulations🎉, you have made a PR to the repository. Wait for your submission to be accepted and your PR to be merged by a maintainer.
Show some ❤️ by starring this repository and do follow me for more updates✨
