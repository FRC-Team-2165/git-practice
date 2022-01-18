# git-practice
A practice repository for learning how to use Git.

If you haven't already, make sure you have a Github account. You'll need it to contribute code.
# Instructions
## Cloning the respository (You'll only do this once per computer)
1. Open Visual Studio Code (VScode), and close all projects if one is open, or open a new window.
2. Navigate to the "Source Control" Tab on the top left side of the screen (the icon that looks like it's branching).
4. In Github, navigate [the git-practice home](https://github.com/FRC-Team-2165/git-practice), and click on the green "Code" dropdown
5. In that dropdown, click to the "HTTPS" tab, if it isn't already selected, then click the copy button at the end of the text field (the two overlapping squares).
6. Back in VScode, click the "Clone Repository" Button. If it isn't there, make sure all projects are closed, then try again.
7. Paste the Github URL you copied into the text area that just opened. You will be prompted to log into your Github account, which you should do now.
8. When the notification in the lower right asks if you want to open the project, do so.

Congratulations! You've just cloned your first git repository! Now you get to learn how to edit your code!

## Editing the repository
1. In VScode, navigate to the "Source Control" tab.
2. Click on the 3 dots on the tob bar of the "Source Control" panel, then navigate down to "Branch > "Create branch...".
3. You will be prompted to enter a name for the branch. Do so, but keep in mind that your name needs to be unique to the project, so in this case, name it after yourself. It's a best practice to do all lowercase, with dashes('-') in place of spaces.
4. You are now on that branch, and you can modify the code as you like. In this case, open into the "students.md" file in VScode (Click on the "Explorer tab - the two sheets of paper", and open the file).
5. In the file, type your full name under the current year, preceded by a dash and a space.
6. Save the file.

Congratulations! You've just editted your first source-controleld file! Now you'll learn how to save your changes in the source control!

## Commit your changes
1. In VScode, navigate to the "Source Control" tab.
2. If you've saved the file, it should appear in the "Changes" part of the panel. Go over to it, then click on the "+" sign that appears. This "stages" your changes for commit, and the file should move to a "Staged Changes" part of the panel.
3. In the text field at the top, type in a short message describing the changes you made.
  - Generally, you should always talk in the present tense e.g. "Add motor controller to drive system".
  - Avoid using pronouns (namely "I", "you", "it", or "they")
  - Keep the messages brief while still being as descriptive and readable as you can make them. To that end, use more or less complete sentences.
4. Click the checkmark above the text field to "commit" your changes.

***Note***: You can do this with any number of files. You don't need to do this every time you make a tiny change. Only when you need to record your work as a sort of milestone. If you're not sure whether you should, ask a mentor.

Now your changes have been saved, so let's share them with everybody else!

## Pushing your changes
1. Once you have commits you haven't shared, in the "Source Control" panel you should see a blue button that says "Publish Branch" if you haven't shared it before. Otherwise you'll see a button that says "Sync Changes", and the number of commits you haven't pushed. Press that.
2. You may see a dialog pop up saying something about "pull" and "push". Just click "okay" or "yes".
3. Go to the project on Github, then click on the dropdown that probably says "master" or "main" at the top right of the files, opposite the green "Code" button from earlier. Select the branch that you just created, i.e. the one named after you. 
  - If you look at the "students.md" file, you should see the changes you just made. If you navigate back to "master", you won't see the changes.
4. Click on the "Pull Requests" at the top of the project (not the one at the top of the page).
5. Click on the green "New Pull Request" button.
  - There may be yellow(?) dialog saying your branch has recent changes with a green "Compare & Pull Request" button. Ignore this.
6. Click the dropdown that says "compare: master" or "compare: main", and select your branch. 
  - You should see the commits you made pop up as well as some comparison windows that show the changes you made.
7. Click the green "Create pull request" button.
8. Give the pull request a title (the text field next to your profile image), and give it more of a description or add any comments you might have in the "Leave a comment" box.
  - The comment box is useful for listing the changes you made in a bullet-pointed form. This makes it easier for the reviewer.
9. Notify one of the programming mentors (presently Kellen Watt), either by telling them in person, or by setting them as a reviewer on the right side (user KellenWatt). They will go in and validate your changes, then merge the pull request.

**Congrats! You're code is now merged into the main respository forever! Good work!**

This will be the major process that you'll follow every time you make changes to robot code. Don't worry if you don't remember it or ge the process perfect every time. We're all human, and git is complicated.
