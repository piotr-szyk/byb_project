## Instructions for the Compulsory Task 1


- Login to GitHub using the account you created in a previous task.
- Create a new repository by selecting the ‘New’ button
- Name the repository ‘byb_project’ and make sure that it is public.
- Next, create an empty folder called **byb_project** on your local machine.
- Open your terminal or command prompt and then change the directory (cd) to your newly created folder.
- Enter the `git init` command to initialize your new repository.
- Enter the `git status` command and make a note of what you see. You should have a clean working directory.
- Create a new file in the byb_project folder called helloWorld.py or helloWorld.js (if you’d like to write in JavaScript) and write a program that prints out the message “Hello World!”.

- Run the `git status` command again. You should now see that your helloWorld.py file is untracked.
- Enter the `git add` command followed by helloWorld.py to start tracking your new file.
- Once again, run the `git status` command. You should now see that your helloWorld.py file is tracked and staged to be committed
- Now that it is tracked, let us change the file helloWorld.py. Change the message printed out by the program to “Git is Awesome!”
- Run `git status` again. You should see that helloWorld.py appears under a section called “Changes not staged for commit”. This means that the file is tracked but has been modified and not yet staged.
- To stage your file, simply run `git add helloWorld.py` again.
- If you run `git status` again you should see that it is once again staged for your next commit.
- You can now commit your changes by running the `git commit -m` command. Remember to enter a suitable commit message after the -m switch.
- Running the `git status` command should now show a clean working directory once again.
- Push the repository on your local machine to the remote repository on GitHub by following these steps
- Open your terminal or command prompt. Change the directory (cd) into the byb_project folder you created.
- Add your remote repository using the following command: `git remote add [remote-name] [url]` e.g. `git remote add origin https://github.com/HyperionDev/byb_project.git`.
- Now you can use the short name (e.g. origin) on the command line in lieu of the whole URL. The URL will be indicated under the heading shown below once you have created your repository on GitHub.
- Push your local repository to your remote repository using the following command:
  `git push -u [remote-name] master`
  `E.g. git push -u origin master`

## Lessons Learnt
The above instructions assume the name of the main branch as `master`. In fact, the default name in GitHub is currently `main`, 
so issuing the following command: `git push -u [remote-name] master` created a second branch (apart from the `main` branch).
I have learned how to rename as well as change the default branch.
