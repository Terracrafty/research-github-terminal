
# Researchuppgift: Git, Github och Terminalen
 
***
 
## Example Bash commands:

	- pwd 
		- Displays active directory.
	- cd [path] 
		- Changes active directory.
	- ls 
		- Lists contents of active directory.
	- mkdir [path]
		- Creates a new directory.
	- rmdir [path]
		- Removes directory. Must be empty.
	- mv [from] [to]
		- Moves specified file or directory to the specified location. Can also be used to rename files/directories.
	- rm [path]
		- Removes specified file.
	- cat [path]
		- Prints the contents of the specified file as text. Use on files that aren't text files to generate infinite mojibake.
	- head [path]
		- Prints the first 10 lines of specified file.
	- tail [path]
		- Prints the last 10 lines of specified file.
	- wc [path]
		- Prints number of lines, words, and characters in the specified file (In that order)

## Example Git commands:
	
	- git init
		- Creates a Git repository in the current directory.
	- git status
		- Displays current branch, modified and staged files, and untracked files that are not set to ignore.
	- git add
		- Adds files to index, to be updated in the next commit.
	- git diff
		- Displays differences between index and current working tree by default. Can also compare things in a number of other ways.
	- git commit
		- Creates a new commit from the current contents of the index.
	- git branch
		- Displays and creates new branches of the repository.
    - git checkout
        - Changes active branch and resets the working tree
        - Being split into git switch and git restore, as it was deemed that git checkout does too many different things which is causing confusion for many users.

## Bonus facts
Git står för "Global Information Tracker" när den fungerar och "Goddamn Idiotic Truckload of sh*t" när den inte gör det.

Markdown använder tab eller 4 mellanslag för att skapa ett kodblock, vilket blev rätt snyggt i det här fallet, men jag bör vara mer försiktig med att organisera text med indentering annars.
	

## Sources

[Bash Cheat Sheet by RehanSaeed](https://github.com/RehanSaeed/Bash-Cheat-Sheet)

[Official Git documentation](https://git-scm.com/docs)

[Difference between git checkout and git switch](https://stackoverflow.com/questions/57265785/whats-the-difference-between-git-switch-and-git-checkout-branch)

[Original Git README](https://github.com/git/git/blob/e83c5163316f89bfbde7d9ab23ca2e25604af290/README)

[Markdown syntax reference](https://www.markdownguide.org/basic-syntax/)
	