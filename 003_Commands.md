```

📁 File Created by : Dhiraj
📧 Gmail  : dhiraj.datascientist@gmail.com 
👨‍💻 Github : dhirajdatascientist
```

# Creating a new Git repository and pushing it to GitHub :

1. Add the `README.md` file to the staging area:

```
git init
git add README.md
```

* This command stages the `README.md` file for committing, which means Git will track changes to this file.

3. Create the first commit with a commit message:

```
git commit -m "first commit"
```

* This creates a commit with the staged changes and adds the provided commit message, "first commit."

4. Rename the default branch to "main":

```
git branch -M main
```

* This command renames the default branch from "master" to "main." This step is optional but is often done for inclusive language.

5. Link your local repository to a remote GitHub repository:

```
git remote add origin https://github.com/dhirajdatascientist/reactjs_CDLC.git
```

* This associates your local repository with a remote repository on GitHub, named "origin," using the specified URL.

6. Push your local "main" branch to the remote GitHub repository:

```
git push -u origin main
```
