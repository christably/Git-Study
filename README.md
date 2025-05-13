# Uploading a folder/directory from our local device to git using the command line.   

## Steps
1. Install Git:

Make sure Git is installed on your computer. If not, download and install it from git-scm.com.
Initialize Git in Your Folder:

2. Open a terminal or Git Bash.
Navigate to your folder using the cd command.
Run git init to initialize a Git repository.
Add Files:

3. Run git add . to stage all files in your folder.

4. Commit the Files:
Run git commit -m "Initial commit" to commit your staged files.
Push to GitHub:

5. Link your local repository to GitHub:
Run git remote add origin https://github.com/your-username/your-repo.git

6. Create the repository on github.(same name)
   
7. Push the files:
Run git push -u origin main

or
git push --set-upstream origin master
type username
type your PAT when it demands for password.

# To verify remote url
Run git remote -v

# To Clone Your Git Repository On Your Local Device
## Steps

Fist create the Repository on Github
1. Run git clone https://personal_access_token@github.com/username/repository_name.git
2. Navigate to the repoitory using 'cd'
3. Add a README.md, files or directories
4. Run git config --global user.email "someone@example.com"
5. Run git config --global user.name "your_name"
6. Run git add .
7. Run git commit -m "commit_message"
8. Run git push

# To Clone A Random Repository
## Steps

1. Run git clone url_of_repository
