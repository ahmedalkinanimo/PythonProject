To upload a Python file from a local folder to a GitHub repository, you can follow these steps:

1. Create a new repository on GitHub by logging into your account and clicking on the "New" button on the repository page.

2. Open a terminal window on your computer and navigate to the local folder where your Python file is located using the "cd" command.

3. Initialize a new Git repository in the folder by running the following command:
code: git init

4. Add the Python file to the Git repository by running the following command:
code:git add filename.py
Replace "filename.py" with the actual name of your Python file.

5. Commit the changes to the repository by running the following command:
code: git commit -m "Initial commit"
Replace "Initial commit" with a descriptive message for your commit.

6. Add the URL of the remote repository to your local repository by running the following command:
code: git remote add origin https://github.com/yourusername/repositoryname.git
Replace "yourusername" with your GitHub username and "repositoryname" with the name of the repository you created in step 1.

7. Push the changes to the remote repository by running the following command:
code: git push -u origin master

This will upload your Python file to the "master" branch of your remote repository on GitHub. If you make changes to the file in the future, you can repeat steps 4-6 and then run "git push" to update the file on GitHub.