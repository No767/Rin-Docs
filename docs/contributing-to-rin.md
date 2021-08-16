# Contributing

We are glad that you're willing to contribute to this project. We are usually very lenient and relaxed with the submissions of PRs, and Issues reports. But there are some stuff that you need to know before contributing.

## Requirements

To get started, you'll need these things installed: 

- Git
- Python 3.6 and above (Made in 3.9.6)
- pip 
- Discord.py
- Python-dotenv
- Cog Watch
- 
Full requirementst.txt list here:
```
discord == 1.7.3
discord.py == 1.7.3
python-dotenv == 0.19.0
qrcode==7.2
image==1.5.33
praw==7.4.0
deviantart==0.1.5
py3-pinterest==1.2.2
tweepy==3.10.0
deep-translator==1.5.0
pyinstrument==4.0.2
black==21.7b0
django>=2.2.18 # not directly required, pinned by Snyk to avoid a vulnerability
pillow>=8.1.0 # not directly required, pinned by Snyk to avoid a vulnerability
```

All of the dependencies that is needed for this project can be found within the `requirements.txt` within the root directory of this project.

## Installing Dependencies

Git can be found [here](https://git-scm.com/). Python can be also found at its website ([Python's Official Website](https://www.python.org/)). And lastly, the Discord.py lib is listed within the requirements.txt file. 

To install the dependencies listed within the requirements.txt, just cd into the project's root directory and  run `pip install -r requirements.txt`.
Or you want to do it manually, run `pip install discord`, `pip install python-dotenv`, and `pip install cogwatch`.

## Pull Requests and Commits

You typically would want to fork the repo, and send all the changes back as a pull request. Though this is fine, it's more preferred to just to commit to the branch itself. The recommended way to do this is to send the pr or commit into the dev branch, then if it's stable enough, it'll be committed into the master branch. There are many ways to do so, and we are pretty chill about it. 

## Issue and Feature Requests Reports

If there is an issue or a feature you want to be added, use the built-in GitHub issue tracker. Though a system like Jira could be used, it would be more efficient to just use the issue tracker that GitHub provides. 

- If submitting a issue report, follow the template. Duplicates will not receive support
- If submitting a feature request, follow the template as well. As with issue reports, duplicate requests will not receive support

## Git Commit StyleGuides

- If updating any other files that aren't project files or not important, add the [skip ci] label in the front
- With each new commit, the message should be more or less describing the changes. Please don't write useless commit messages...

## Code StyleGuides

- Use the PEP 8 Standard if possible
- Use patches if possible (not needed, but if you want to, go ahead)
- Space out the code. This makes it way easier to read