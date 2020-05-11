Adding an existing project to GitHub using the command line

<li>Create a new repository on GitHub. You can also add a gitignore file, a readme and a licence if you want</li>
<li>Open Git Bash</li>
<li>Change the current working directory to your local project.</li>

<li>Initialize the local directory as a Git repository.</li>
	<ul>git init</ul>

<li>Add the files in your new local repository. This stages them for the first commit.</li>
	<ul>git add .</ul>

<li>Commit the files that you’ve staged in your local repository.</li>
	<ul>git commit -m "initial commit"</ul>
 
<li>Copy the https url of your newly created repo</li>

<li>In the Command prompt, add the URL for the remote repository where your local repository will be pushed.</li>
	<ul>git remote add origin remote repository URL</ul>
	<ul>git remote -v</ul>
 
<li>Push the changes in your local repository to GitHub.</li>
	<ul>git push -f origin master</ul>