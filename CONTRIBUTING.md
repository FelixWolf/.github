# Contributing
Want to help make this project even better(or worse, depending on the type of project!)? Great!

If you are new to contributing, this document will have all you need to know to create a issue or change.
If you are old, feel free to skip the stuff you already know.

# Code of Conduct
If you don't know how to behave, please review [Code of Conduct](code_of_conduct.md). Otherwise, just be nice!

# Reporting an bug or requesting a feature
Reporting issues can differ from platform to platform. Select the one that applies to you:

## Github
Github does not accept anonymous issues, you will need an account to do so.
If you do not have a github account, please refer to https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account

1. Click the "Issues" tab below the project name: <br/>
![btn_issues](https://user-images.githubusercontent.com/6495643/169618057-800ffbce-d4b1-4e5c-9847-a656fc43770a.png#gh-dark-mode-only) ![btn_issues](https://user-images.githubusercontent.com/6495643/169618560-c9def760-d025-4898-93f7-5adc812bbbd3.png#gh-light-mode-only)
2. Click the "New Issue" button: <br/>
![new_issue](https://user-images.githubusercontent.com/6495643/169618842-bc4116ba-4e6c-414e-a360-8fdcd3d27d20.png)
3. Find the template that best matches your issue type and click the "Get Started" button: <br/>
![get_started](https://user-images.githubusercontent.com/6495643/169619108-f81d2b71-443f-426d-852b-c18d65668ca0.png)
4. Fill a summary of your issue in the single line field.
5. In the multi-line field, you should replace the placeholder text for each section with your own text.
6. Review your report, be sure that you don't include any personal information(Unless you want to)!
7. Click "Submit new issue": <br/>
![submit_issue](https://user-images.githubusercontent.com/6495643/169619437-cbfd20c3-41bb-473b-aa49-bd0794b31034.png)

You're all set and your issue is now live! It'll be reviewed by a contributor given due time.

# Contributing code

## Setting up git
### Windows and Mac users
You can download git from here: https://git-scm.com/downloads
### \*NIX users
Git should be able to be installed from your package manager, eg:
Debian: `apt-get install git`
Archlinux: `pacman -S git`

Alternatively, You can download git from here: https://git-scm.com/downloads

### Forking a repo
#### Github
Simply click the "Fork" button at the top right of your browser window!

### Downloading the repo
1. Open a terminal or command prompt and navigate to the directory you wish to clone the repo in. (It'll be made in a subfolder)
2. Type `git clone <repo url>` (Without the `<>`s)
3. Wait for it to download, it may take some time if it is a large repo.
4. View your copy in your favourite filesystem browser and code editor!

### Setting your identity
This is only needed if you want to *PUSH* code.
1. Open a terminal or command prompt.
2. Type `git config --global user.email "<Your Email>"`
3. Type `git config --global user.name "<Your Name>"`

### Staging a change
Once you have changed the code you wanted to change:
1. Open a terminal or command prompt and navigate to the location the code is at. This can be the subfolder you cloned, or any where in it!
2. Type `git add <filename>` with the name and path of the file. It is relative to the current directory the terminal is in. You can add multiple files by seperating them by spaces!
3. Type `git commit -m "<change summary>"` (You can omit `-m "<change summary>"` if you have a terminal editor configured to get detailed commit info)

Your change is now staged!

### Adding a SSH key
#### Github
Please refer to https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

### Pushing your change
**IMPORTANT**: You *cannot* push changes to a repo you do not have permissions to do so on. You should push to your fork instead! If you need to change the upstream path by typing `git remote set-url origin <your fork URL here>`.
Once you are satisfied with your changes:
1. Open a terminal or command prompt and navigate to the location the code is at. This can be the subfolder you cloned, or any where in it!
2. Type `git push`
3. If prompted for a username and password, enter it. It'll be the same information on the site you are pushing to.
4. Your changes are pushed!
