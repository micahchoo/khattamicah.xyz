---
title: How to use Github to collaborate on Obsidian privately
tags: knowledgemanagement
toc: false
season: spring
---

1. Create a Github Account (eg. MyGithubsUserName) - this will be shared among your collaborators
2. Create a **Private** Repository (eg. MyFolderFor_Obsidian)
3. On your local machine open the terminal to the folder where you want to store the notes
	1.	[you can find instructions here](https://www.groovypost.com/howto/open-command-window-terminal-window-specific-folder-windows-mac-linux/#:~:text=Go%20to%20the%20folder%20you,directly%20to%20the%20selected%20folder)
4. Once the terminal is open type in git clone https://MyUserName:MyPasswordfortheaccount@github.com/MyUserName/MyFolderFor_Obsidian.git replace the placeholders i have put with your username password and foldername in github
5. Install [Github Desktop](https://desktop.github.com)- only available for Windows and Mac. The other way to do this is through the terminal which I haven't figured out yet
6. Open Obsidian (assuming you have installed it already) - on the left hand bar there should be a "Open a New Vault"
7. There choose "Open folder as Vault" and choose the folder from step 3. This should Create a new folder for notes you want to collaborate on. Just for testing purposes create a new note
8. Open and login to Github Desktop. When it asks to add a repository. Choose "Add an existing Repository" and go to the folder from step 3
9. On the left side you should see the new file you created come up as changes
10. On the top you'll see "Fetch Origin" click that to pull any changes that other have made to the github repository. Do that.
11. If you are satisfied with the changes - On the left you'll see "commit to main". click that with the necessary comments
### the problem
with this method is that two people cannot work on the same file together. to solve this
12. On Github Desktop, you'll see an option called current branch, open that and create a new branch under your name - this is the branch you will always commit to. it creates a different version of the vault
13. I'm not sure what a good time to merge is- but i'm hoping that once you look at main and see that there are no new changes to that particular file you have made, you can merge yournamebranch into main
14. for merging you can see an option under "Current Branch"
---
15. (From 7) Once installed, Obsidian will ask you if you want to install community plugins, say yes then go to Settings>Community Plugins and switch on all the plugins you use
# Actions to perform
1. Commit -> Push to Origin - sends your changes to the web version of your github folder
2. Fetch Origin - updates your local github folder by copying what new things are there on the web version of the github folder
3. Merge yourbranchname into main -  brings your changes from your branch to the main branch

# Workflow
1. after testing, i Think the best way to work with a team is to start every session of writing by fetching from origin in the beginning.
2. If there is a conflict, stash changes is a good option
3. While working commit every hour or halfhour
4. Possibilities: Cron jobs to backup local copy every 5 minutes and every 50 mins and every 48 hours. 