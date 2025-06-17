Step 1: Download git
	[Git - Downloads](https://git-scm.com/downloads)
Step 2: Open cmd.exe
Step 3: Go to the directory in which you want to store your Obsidian Vault
		For Example: I navigated to C:\Tredracomundus
		Utilize "cd .." to go back a directory, if you need to
Step 4: type "git clone https://github.com/QuadraticKing/ICBM_Notes"
	This will Clone the git repo to the directory you set up in Step 3
Step 5: In Obsidian, in the bottom left select your current vault name, and select "Manage Vaults"
Step 6: Create a *new* Vault called ICBM_Notes, and set the folder where you set the Git Repo as the directory. This will sync the git directory to your repo
Step 7: In Obsidian, create a new note and write some stuff in it.
	This is how you'll test whether your git is connected.
Step 8: In CMD type "git status". If you see your note in red text, that means that you've made changes to *your* repository that aren't reflected in the *public* repository
Step 9: Type "git add ." to add that file to a cache to be pushed
Step 10: Type "git commit -m "*Commit Message*"" The Commit message can be anything, but it is usually a brief 3-5 word summary of what you touched
Step 11: Type "git push". This will push your changes to the public repo
	If you get prompted for a Username, input your GitHub username
	If you get prompted for a Password, input "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"
Step 12: If this doesn't work, You can troubleshoot by downloading GitHub Desktop [Download GitHub Desktop | GitHub Desktop](https://desktop.github.com/download/) or wait until Saturday where we can work together on it. 
