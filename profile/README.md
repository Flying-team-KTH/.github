# Welcome to the Github organisation of the KTH flying team

The purpuse of this organisation to provide a way to systematise
different flying project. TODO

This document contains further tutorials on how to download each project. 

>However, it is advisable to contact the person responsible for the structure used in each project.

> **DISCLAIMER:** All repositories should be considered public until the user is assured otherwise.

## Basic usage of Git and Github

A quick tutorial on how to download a GitHub project from an organization using the terminal:

1. Open a terminal window on your computer.

2. Navigate to the directory where you want to download the project. You can do this by using the `cd` command. For example, if you want to download the project to your **Desktop**, you can use the command:

   ```
   cd ~/Desktop
   ```

3. Use the `git clone` command to download the repository. For example, if the organization's name is **ExampleOrg** and the repository name is **TestRepository**, you can use the command:

   ```
   git clone https://github.com/ExampleOrg/TestRepository.git
   ```

   This command will download the entire repository to a new folder named **TestRepository** in your current directory.

4. Once the repository has finished downloading, navigate into the **TestRepository** folder using the `cd` command:

   ```
   cd TestRepository
   ```

5. You should now be able to access the files in the repository and make any changes or modifications as needed.

And that's it! You should now have the TestRepository project downloaded to your computer and ready to use.


> **DISCLAIMER:** Git needs to be installed to one's PC to be able to do it.



A quick summary of how to use the basic **Git** commands:

1. `git status`: This command shows you the current status of your Git repository, including any changes that have been made to files, files that have been added or deleted, and files that are staged for commit.

2. `git add`: This command adds changes to the staging area, which is where you prepare changes to be committed. You can use the command `git add <filename>` to add specific files or `git add .` to add all changes in the current directory.

3. `git commit`: This command creates a new commit with the changes you've added to the staging area. You can use the command `git commit -m "<commit message>"` to create a commit with a message describing the changes.

4. `git push`: This command uploads your local commits to the remote repository on GitHub or another Git hosting service. You can use the command `git push <remote> <branch>` to push your changes to a specific remote repository and branch.

5. `git pull`: This command downloads any changes from the remote repository and merges them into your local repository. You can use the command `git pull <remote> <branch>` to pull changes from a specific remote repository and branch.

These are just the basic Git commands, and there are many more advanced features and workflows available. However, understanding and using these basic commands should be enough to get started with version control using Git. If more information is needed contact someone with proper knowledge.




<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
