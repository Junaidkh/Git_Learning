Adding an existing project to GitHub using the command line

<li>Create a new repository on GitHub. You can also add a gitignore file, a readme and a licence if you want
<li>Open Git Bash
<li>Change the current working directory to your local project.

<li>Initialize the local directory as a Git repository.
	<ul>git init

<li>Add the files in your new local repository. This stages them for the first commit.
	<ul>git add .

<li>Commit the files that you’ve staged in your local repository.
	<ul>git commit -m "initial commit"
 
<li>Copy the https url of your newly created repo

<li>In the Command prompt, add the URL for the remote repository where your local repository will be pushed.
	<ul>git remote add origin remote repository URL
	<ul>git remote -v
 
<li>Push the changes in your local repository to GitHub.
	<ul>git push -f origin master