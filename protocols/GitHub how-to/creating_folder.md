## Creating (sub)folders and uploading data

Have you finished another day of surveying? That's amazing! To upload your survey metadata and data files, follow these steps:

**1**. Make sure you are on your 'main' branch.

![image](https://github.com/user-attachments/assets/7caa24fb-7581-4746-b3b6-faac03749165)

**2**. Navigate to the `data` folder, click `Add file` and then `+ Create new file` in the top right corner.

![image](https://github.com/user-attachments/assets/c1b7afec-394b-46ed-9171-dfa01ea74907)

**3**. Where it says `Name your file...` add the name of the folder you want to create, followed by a `/`. For example, this could be the 2025-02-12_survey. By adding a / at the end, you've created your folder.

![image](https://github.com/user-attachments/assets/7669a39b-767e-4080-85df-c6be828a5c56)

**4**. Unfortunately, through the GitHub web UI it is not possible to create empty folders, nor create multiple folders at the same time. Therefore you'll have to add a file here called `.gitkeep`. Don't worry, this is an 'empty' file and doesn't affect the repository in any way.

![image](https://github.com/user-attachments/assets/00723af0-2194-4ae6-acdb-11d116b710e5)

**5**. In the top-right corner, select the green button 'Commit changes...'

![image](https://github.com/user-attachments/assets/5b90148f-d080-437b-84d9-15b5ece41f56)

**6**. Next, select 'Create a new branch for this commit and start a pull request'. Essentially what it does - if you consider 'main' to be the tree trunk - it creates a separate branch that runs parallel to the 'main'. You will be able to make changes to this branch, that you can name, without it affecting your main branch. This way we'll try and keep the main branch as 'clean' as possible! Indeed, as you can see, you won't be able to make any direct commits to the `main` branch. Add a commit message at the top - in the future this might help you navigate to previous commits. In the bottom right corner, select 'Propose changes'. 

![image](https://github.com/user-attachments/assets/adc656bf-ca69-4724-9c68-e64cd075213b)

**7**. This will bring you to a page where you can Open a Pull Request. At the top you'll see what branch you wish to merge into the 'base' branch (`main`). Create a pull request at the bottom right. 

![image](https://github.com/user-attachments/assets/98ad04ec-fa93-4c2c-b476-28513a7246ee)

**8**. You'll see your open pull request. _Please note: opening a pull request **is not** the same as merging the pull request_. You can still make and commit changes in this specific branch, and these will be reflected in this pull request as well. You'll also see that in the background, there will be some checks done to make sure that the data provided is properly populated, and files and folders follow a specific naming convention. These checks will run every time you make a commit to this branch.

![image](https://github.com/user-attachments/assets/eaa29ccf-7f14-4f74-a781-39d839288ef6)

**9**. Navigate back to the root of the repository by clicking `Code` in the top left. **Make sure you navigate to your newly created branch!** Then, navigate to your newly created subfolder (e.g., `data/2025-02-15_survey`). You'll notice that this folder is still empty, except for the .gitkeep file. Next, **you will have to create each folder for the instrument-specific data in a separate commit!** To create those 3 folders, make sure you are in the correct survey folder. 

![image](https://github.com/user-attachments/assets/8643cb7a-5cc7-4b38-8bcc-2582f5a48090)

**10**. When creating the new subfolder (Add file -> + Create new file), you will again have to populate these with a .gitkeep file (e.g., Aquafluor/.gitkeep). Select 'Commit changes...' in the top right corner again. These changes can be committed **directly** to the new branch you created. Make sure you add a commit message.

![image](https://github.com/user-attachments/assets/d0a6a619-a1a1-4cca-9d56-4ab20c5981bb)

**11**. Once you've done that for each subfolder (Instruments, DR1900 and Aquafluor), it's time to upload all your data files. Thankfully this is a lot easier, and it's a simple matter of dragging and dropping them into the correct folder, and committing this. Upload your files by selecting 'Add file' -> 'Upload files'.

![image](https://github.com/user-attachments/assets/a24721ec-fa57-478e-a980-e8e72c95da63)

Few things to confirm: 
> 1) check you're in the correct branch, 
> 2) make sure you're in the correct (sub)folder, 
> 3) your files follow the correct naming convention. 

**12**. Drag files, or choose files, to add them to the repository. Then commit directly to the new branch you created.

![image](https://github.com/user-attachments/assets/99065155-87ea-4589-9f0d-204291105a19)

To see an example of what a populated survey folder looks like, see the 2024-09-16_example_dataset folder under `data`.
