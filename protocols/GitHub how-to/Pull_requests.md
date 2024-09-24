If you have followed the steps on how to create additional (sub)folders within your data folder, and how to populate them with your survey and data files, you now have branches: your `main` branch, and the branch you have created for the survey data collected that day. The next steps will be merging the new branch into your `main` branch. You can do so through a **Pull Request**!

First, let's understand what a pull request (PR) actually is. In essence, with a pull request, you are _requesting one branch to be merged with, or pulled into, another branch_. In our case, we want to merge the new branch into the main. This way we can keep all the files and formats that have been processed and named properly into a single repository branch, the `main` branch. 

To do a pull request, follow these steps:

1. Now you have populated the data files into their respective folders, it's time to merge, or join, this branch into the 'main' branch. If your survey folder and files are properly formatted, this will be no problem! Navigate to the top of your repository and select ....

[insert picture]

2. Next, you can open a 'pull-request' (PR). By opening a pull request, basically what you're asking is for the new branch to be 'pulled into' the main branch. There will be a few checks - on GitHub's side and those that might get implemented by the GEM Data Team - to ensure that this can be done safely without the need to modify the organization of the main branch. Select 'Open Pull Request'

[insert picture]

3. Here's you'll see your various commits that you made (creating the folders, uploading your data), and the differences in files between your main branch and your new branch. If all checks are complete (green checkmark) you can safely merge this branch into your main!

[insert picture]

4. If any of the checks fail, you'll see a red cross, indicating that something's wrong - this might be as simple as a file being wrongly named, or a little more challenging to deal with. Either way, whenever a check fails, an _issue_ will be created to describe what the problem is and what needs to be done for it to get resolved. Someone from the GEM Data Team will also be assigned to that issue and can help you resolve it.

[insert picture]

5. If all the checks have complete and have merged the branch into main - CONGRATS! You should now see your data in the main branch of your repository!
