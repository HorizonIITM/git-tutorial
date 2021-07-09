# git-tutorial
Repository used for demonstrating git, and giving task. (Part of CFI Summer School 2021)

# Task
1. Fork this repository.
2. Clone the forked repository to your system and create a new branch with your Roll Number as the branch name (in lowercase).
3. Activate the newly created branch.
4. Create a file named your roll number (in lowercase) inside the [`submissions`](./submissions/) directory, 
   with the following contents (please read **Instructions** before doing this:
```
your-roll-number
your-linux-username
current date and time
current memory details
```
5. Some of the commands that you may use to achieve this include `whoami`, `date`, `free`, `grep`, `cat`.
6. Add this new file to the your local repository, commit it (short commit message will suffice), 
   and push the changes to GitHub (pushing will throw error: follow the instruction in the error to push).
8. Open Pull Request in the original repository with the newly added file as instructed above. The title
   of the pull request should be in the format `rollnumber_name` (in lowercase). In the description briefly write
   what you learnt in the Linux module, and what more would you have liked to learn. Check the **Pull-Request**
   section for how to make PRs.
8. Complete the circulated Google Form by uploading a text file containing all the commands that you used
   to create the file in **step 4**.
9. Now wait!

# Instructions
1. Only terminal and command-line should be used for **steps 2 till 6**. And all of the commands used
   for the steps should be specified in the text file that you upload in Google Form. Please enter
   **all** the commands. When we try your series of commands, and if it doesn't evaluate to the
   desired output, you won't be passing this task.
2. No editors of any kind should be used at any part from **step 2 till 6**. This includes but limits to
   the prohibition of the following: Vi, ViM, Emacs, Neovim, Kakoune, Nano, Atom, VS Code, Sublime,
   Gedit, etc. **tl;dr** DO NOT USE ANY EDITORS (TERMINAL AND GUI) FOR STEPS 2 TILL 6.
3. You are free to use any commands available in a fresh installation of Ubuntu. Commands/Tools from
   user installed packages should not be used (exception being git).
4. The memory details in fourth line of the file should not contain any information about Swap memory,
   or any column headers. Consult the example file [`ph19b003`](./submissions/ph19b003) to get an idea.
5. Make sure the file you upload to Google Forms is a plain text file (you can confirm using the `file` command,
   and all of the commands used in creating the file in **step 4** are provided.
   
# Pull-Request
1. After pushing your changes in the newly created branch to your forked repository, open the
   forked GitHub repository in your browser.
2. If you have successfully completed until step 6, you will see a notification with a button `Compare and pull request`.
   Choose that.
3. You will have some dialogs with options. Make sure the following are correct:
   1. `base-repository` should be the original Horizon's **git-tutorial** repository.
   2. `base branch` should be **main**.
   3. `head-repository` should be your forked repository.
   4. `head-branch` should be the branch named your roll-number, which you created and pushed.
4. If all steps are done correctly, it should show **Able to merge**.
5. For the pull request title enter `rollnumber_name`, where `rollnumber` is your rollnumber and `name` is your name.
   All characters should be lowercase, replace spaces in your name with `-` (hyphen).
6. Write a small description about what you learnt in Module 1.1 and what you expected, but didn't learn.
7. Click `Create pull request`.
