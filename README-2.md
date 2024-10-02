# How to Create and Connect a Github Repository
![Suspicious guy sitting in front of two monitors](https://images.unsplash.com/photo-1654095923893-6a255e5ed4d3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OXx8Z2l0aHVifGVufDB8fDB8fHww)
## In Git Bash Terminal:
1. `cd` to the directory where you want to create your repository.
> _Tip: you can also use `mkdir` to create a new directory to hold your files. However, ensure you navigate to it before executing the next command._
2. Run `git init`. This will turn your folder into a git repository.

3. Create the files that you want to upload to GitHub. You can use the `touch` command followed by the file name and extension.

**Example:**
```
cd example/directory/tutorial

mkdir github-repo-tutorial

cd github-repo-tutorial

touch index.html style.css script.js
```

4. Open VSCode using `code .` command.

## On GitHub Website
1. Create a new repository using the green button.

2. Name your repository and set it to public before launching it.

3. Copy the link that showed up in the instructions page.

> *It should look something like this: `https://github.com/your-username/your-repository.git`*

## Back to the Terminal
Execute the following commands:
```
git add .

git commit -m "comment your changes"

git remote add origin https://github.com/your-username/your-repository.git

git push origin main
```

and ***Voila!*** You have just connected your local repository to the remote one on GitHub.

For more information, visit the [GitHub](https://github.com/) website.