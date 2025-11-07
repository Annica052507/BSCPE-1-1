Installing Git

Visit git-scm.com and download Git.

Follow the installation guide based on your computer’s operating system.

Once downloaded, locate the installer in your file manager and open it.

Continue clicking “Next” through the default setup options until the installation finishes.

Installing Visual Studio Code (VS Code)

Go to code.visualstudio.com and download Visual Studio Code.

Follow the setup instructions for your operating system.

After downloading, open the installer from your file manager.

Click “Next” on all the default options until installation is complete.

Creating a GitHub Account

Open github.com and sign up for a free account if you don’t have one yet.

After registering, verify your email address to activate your account.

Creating a GitHub Repository

Sign in to your GitHub account.

Click the “+” icon in the upper-right corner and choose “New repository.”

Enter a name for your repository (for example, my-first-repo) and optionally add a description.

Click “Create repository” to finalize the setup.

Setting Up Your Project

Create a folder on your computer to store your project files.

Open VS Code, go to File > Open Folder, and select the folder you created.

Open the terminal by clicking View > Terminal in VS Code.

In the terminal, change the shell to Git Bash instead of PowerShell.

Enter the following commands one by one to initialize Git and connect your local project to your GitHub repository:

git init
git config --global user.name "Your Name"
git config --global user.email "you@youraddress.com"
git config --global push.default matching
git config --global alias.co checkout

Next, type the following commands to set up and push your project:

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Annica052507/BSCPE-1-1
git push -u origin main

Before running the above commands, make sure your project folder contains a file named README.md.

Once done, refresh your GitHub page to see your uploaded files and changes.
