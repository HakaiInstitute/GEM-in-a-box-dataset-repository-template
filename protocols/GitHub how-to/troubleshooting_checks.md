## Troubleshooting checks

Ah! So you've opened a pull request, and you see that there is one or multiple checks that have failed! Please don't worry -- these checks are there to ensure that the file naming conventions are followed, files are stored in the correct format, and that required (sub)folders exist. It's just making sure that, in the future, all the data can be easily integrated across the program and made available through data portals. But, I'm getting ahead of myself - how do we know which checks have failed and how can we resolve this? 

**1.** Select 'Show all checks'. This will show you which check has failed. In the example below, the 'Test dataset' check has failed. Let's investigate what exactly is wrong by selecting 'Details'.

![image](https://github.com/user-attachments/assets/37c387f8-d05c-4b07-ac76-e6cbcd0cbeac)

**2.** Forget the next page you see, that shows all the different steps done in this check, and exactly where it's failed. However, it's not very pleasant on the eyes. Instead, navigate to 'Summary':

![image](https://github.com/user-attachments/assets/593138b9-929d-47d9-b11c-c5a37c4cced9)

**3.** Scroll down to where it says 'tests summary'. Here you can see which tests passed, and which failed. In the example below, 20 results (100%) failed. Whoops! But which exactly? That's highlighted in the _failed_ section below. You can expand each failed result by clicking on the arrow:

![image](https://github.com/user-attachments/assets/992ab545-e5a6-46e8-a8e4-31b1c585dc49)

I'm sure you will quickly become familiar with the language used in these tests. In the example above, the folder 'data/20240910_survey' that was created does not follow the GEM naming conventions. The naming used here is YYYYMMDD, but we're looking for YYYY-MM-DD! So this will have to be changed accordingly. In the second and third failed test, you see that we're expecting each data survey folder to have a `_survey_final.csv` and `_survey_raw.jpg` file, but these are not included in the folder, so they'll have to be added. 

_Even if you have failed checks you can still merge the branch. **However**, we strongly encourage you to attempt to resolve each check before merging, as this will make data integration in the future much easier, and therefore your data much more valuable!_

If you get stuck with some tests, please do not hesitate to contact me at tim.vanderstap@hakai.org or create an issue where you can tag me.

