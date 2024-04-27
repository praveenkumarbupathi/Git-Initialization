# Git-Initialization

# configure commands
      
      $git config --global user.name "Your Name"

      $git config --global user.email "youremail@example.com"


# Check existing user 
$git config --list


# First time Initialization 
$git config --global user.name "Your Name"
$git config --global user.email "youremail@example.com"

# Initializing a Repository: 
Navigate to your project folder and initialize a Git repository.
      
      $git init
Add files to the staging area

      $git add <filename>

Save staged changes to the repository.

      $git commit -m "Your commit message"

# Add Remote Repository
If you haven't already created a repository on a Git hosting service like GitHub, GitLab, or Bitbucket, you can create one there. Then, link your local repository to the remote one using the following command:

      $ git remote add origin <remote_repository_url>
# Push Initial Commit: 
After adding and committing your files, push them to the remote repository:

      $ git push -u origin master
