# DnDorks-Daggerheart

## How to Use Git and GitHub with Obsidian
### First Steps
Follow these steps to clone the existing DnDorks-Daggerheart repository so that you can contribute to the groups' notes

1. Install [Git](https://git-scm.com/) to your computer
2. Create a [GitHub](https://github.com/) account
3. Tell Kai that you are ready to be added as a collaborator on the GitHub repository
	1. He will add your GitHub account
4. Navigate to the folder that you want to store your instance of the Vault in
	1. Windows: right click in the file explorer and select "Open in Terminal"
5. Type "git clone https://github.com/kaicachen/DnDorks-Daggerheart.git" into your Terminal and hit "Enter"
6. Open Obsidian and select "Open folder as fault", then select the folder you cloned the repository into
### Adding Git Plugin for Obsidian
Follow these steps to use a GUI in Obsidian to execute Git commands

1. Open your Obsidian vault for the DnDorks-Daggerheart repository
2. Click on the settings gear (usually in the bottom left, depending on your current theme)
3. Click on "Community Plugins"
4. Click on "Turn on Community Plugins"
5. Under "Community Plugins", click on the "Browse" button
6. Search for "Git", then click on the first result
7. Click on the "Install" button, then the "Enable" button
8. Close the Community Plugins window, then click on "Git" under the "Community Plugins" tab in the left side of the Settings menu
	- If you see the message "Git is not ready. When all settings are correct you can configure commit-sync, etc." at the top, then ask Kai for help
### Add Your DM Folder(s) to .gitignore
Add any folders that you do not want shared with other players to the file .gitignore. For more information, see "Where to Place Files/Files for DM Use (Not Visible to Players)"
### Git Commit (Staging Changes)
Adds all changed files not included in .gitignore
- Open Command Palette (either on left side of Obsidian with >\_ symbol, or with ctrl/cmd+p)
- Search for Git: Commit
- Select Git: Commit
### Git Push (Sending Changes to Others)
Pushes all changed files not included in .gitignore to Github for other players to see
- Open Command Palette (either on left side of Obsidian with >\_ symbol, or with ctrl/cmd+p)
- Search for Git: Push
- Select Git: Push
### Git Pull (Receiving Changes from Others)
Pulls all changed files from Github (see other peoples' pushed changes)
*This should be done every time you open Obsidian to make changes*
- Open Command Palette (either on left side of Obsidian with >\_ symbol, or with ctrl/cmd+p)
- Search for Git: Pull
- Select Git: Pull
### Removing Files from GitHub
Follow these steps if you have accidentally pushed files to GitHub that you no longer want to be published there (probably DM notes)
*Please be considerate and only remove files owned by you*

Windows Instructions:
1. Navigate in file explorer to the folder that contains your local copy of the Obsidian vault
2. Right click in the file explorer and select "Open in Terminal"
3. Type "git rm --cached -r '<folder/file name>'" then press "Enter"
4. Repeat step 3 for all desired folders and files
5. Type "git commit" then press "Enter"
6. Type "git push" then press "Enter"
## Where to Place Files
When you are writing your DM notes, you should make a copy of any file that you want players to be able to reference in this vault
- One copy should live in a parent folder where you keep all of your DM notes
- One copy should live in the "Player View" folder
### Files for DM Use (Not Visible to Players)
- Create folder that is a direct child of the root "DnDorks-Daggerheart" folder
- Add the name of this folder to a new line in ".gitignore"
	- If there are spaces in the name of this folder, surround the name of the folder with single quotes 'like this'
	- This acts as a "negative key" to keep files hidden from players
### Files for Player Use (Visible to Everyone)
- Place in "Player View" folder
## Tags
Tags are used for referencing in Obsidian Bases (mini database queries)
### Files for Player Use (Visible to Everyone)
- Add the tag "playerview" to any files you want to be able to reference in Bases within the "Player View" folder
### Files for DM Use (Not Visible to Players)
- If you would like to add a "positive key" to your DM note files, then add a personal tag to your DM files such as "#\<name>dm"
	- This may be done in the event that after you have DM'd a session, you would like to share some or all of your notes, but would also like to ensure Bases reference the correct files
	- This will also help keep files from bleeding into other people's Bases
### General File Identifying Tags
- pc -> player character
- npc -> non player character
- island -> island (duh)
- group -> group (duh)
## Properties
Properties are used for quickly viewing information about files within Bases. Properties cannot be directly referenced to change what files are shown in a Base
### Character Properties
- class -> character class
- race -> character race
- groups -> groups this character belongs to
- allegiances -> groups this character is allied to (NPC)
- enemies -> groups this character is enemies with (NPC)
### Group Properties
- allegiances -> groups this group is allied to
- enemies -> groups this group is enemies with
## Images
All images (such as covers for Card views) should be placed in the "Images" folder. While we could have separate folders for Player View images and DM images, I think it's more fun to let the players have a sneak preview of any upcoming characters they may meet. I have named the sensitive DM image files as the initials of the character they represent, that way there is little information to be gleaned aside from the appearance of the character in the file itself.

Please try to keep the file size as low as possible, as images can take up a lot of storage space.