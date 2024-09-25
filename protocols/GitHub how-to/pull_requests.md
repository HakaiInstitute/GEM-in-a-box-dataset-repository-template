## Opening and merging pull requests

If you have followed the steps on how to create additional (sub)folders within your data folder, and how to populate them with your survey and data files, you now have two branches: your `main` branch, and the branch you have created for the survey data collected that day. The next steps will be merging the new branch into your `main` branch. You can do so through a **Pull Request**!

First, let's understand what a pull request (PR) actually is. In essence, with a pull request, you are _requesting one branch to be merged with, or pulled into, another branch_. In our case, we want to merge the new branch into the main. This way we can keep all the files and formats that have been processed and named properly into a single repository branch, the `main` branch. 

To do a pull request, follow these steps:

1. Now you have populated the data files into their respective folders, it's time to merge, or join, this branch into the 'main' branch. If your survey folder and files are properly formatted, this will be no problem! Navigate to the top of your repository, select "Pull requests" and select the green box 'New pull request'. By opening a pull request, basically what you're asking is for the new branch to be 'pulled into' the main branch. There will be a few checks on GitHub's side and those that might get implemented by the GEM Data Team to ensure that this can be done safely without the need to modify the organization of the main branch. 

![image](https://github.com/user-attachments/assets/29055a6b-d8d1-4240-8d15-df2475f0c51e)

_Please note: You can also open your pull request when you first create a separate branch! Any additional commits you make (i.e. when you create additional data folders or upload data files) into that branch will be reflected within that pull request as well._

2. When you've selected 'New pull request', you can select the branch you want to 'pull' into your main branch. In the example below, we want to merge the branch 'CarrieWeekes-patch-1' into the main branch. GitHub indicates that merging this branch into main can be done automatically. Next, you can ' create pull-request' (PR). 

![image](https://github.com/user-attachments/assets/e6df8e56-1e7d-4e12-a59e-62fbbbd10fbd)

3. Here you can add a title and a description of your pull request before selecting 'Create pull request'. At the bottom you can also see your commits and the files that have been changed in this branch compared to the base branch ('main'). 

![image](https://github.com/user-attachments/assets/fb9f6531-e9c1-4e2e-a233-55a048343132)

4. In the pull request, you'll see at the top of the page which branches you'll want to merge. Confirm these are the correct branches. In the example below, we want to merge 'CarrieWeekes-patch-1' into main. You can also see that there's a few tabs that you can select (Conversation, Commits, Checks, and Files Changed). Any comments in this pull request will be added to the Conversation. You can also verify what files have changed, and in which commits. When a pull request is opened, everytime a commit is made to that branch (CarrieWeekes-patch-1) there will be some checks run automatically by 'github-actions'. If any of the checks fail, you'll see a red cross, indicating that something's wrong - this might be as simple as a file being wrongly named, or a little more challenging to deal with. To understand how to troubleshoot any errors, see [troubleshooting checks](https://github.com/HakaiInstitute/GEM-in-a-box-dataset-repository-template/blob/timvdstap-patch-4/protocols/GitHub%20how-to/troubleshooting_checks.md). 

![image](https://github.com/user-attachments/assets/86c6c637-bc33-42d7-aeb8-7fd99f2807b1)

5. If all the checks have passed, you can merge the pull request. CONGRATS! You should now see your data in the main branch of your repository!

![image](https://github.com/user-attachments/assets/a54c4b06-1af3-4a95-9bf1-c8ee55c08297)

