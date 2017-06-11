# Learning Ruby Notes  


0. Introduction
	* Why do we need to learn this?
		- Learn how to simply manipulate computers
		- Simple but foundational language
		- Familiarizes with directory and file manipulation
	* Lots of memorization
		- Notecards are suggested

1. Exercise 1: The Setup
  * Linux/OSX Commands
		* pwd
			~ print working directory
		* hostname
			~ my computer's network name
		* mkdir
			~ make directory
		* cd
			~ change directory
		* ls
			~ list directory
		* rmdir
			~ remove directory
		* pushd
			~ push directory
		* popd
			~ pop directory
		* cp
			~ copy a file or directory
		* mv
			~ move a file or directory
		* less
			~ page through a file
		* cat
			~ print the whole file
		* xargs
			~ execute arguments
		* find
			~ find files
		* grep
			~ find things inside files
		* man
			~ read a manual page
		* apropos
			~ find what man page is appropriate
		* env
			~ look at your environment
		* echo
			~ print some arguments
		* export
			~ export/set a new environment variable
		* exit
			~ exit the shell
		* sudo
			~ DANGER! become super user root DANGER!

2. Exercise 2: Paths, Folders, Directories (pwd)
 * The ">" symbol is used to prompt the user ($ for Unix)
 * pwd stands for "print working directory"

3. Exercise 3: If You Get Lost
 * To go to default path, type 'cd ~'
 * Print pwd and then cd ~

4. Exercise 4: Make A Directory
 * Make new Directory by using 'mkdir' and 'mkdir -p' for bigger directories for Linux/OSX
 * Directories are the same as folders
 * / can be used, but \ is the usual one to use

5. Exercise 5: Change Directory (cd)
 * Use '..' to navigate up the tree/path

6. Exercise 6: List Directory (ls)
 * dir -r and ls -lr print absolutely everytning

7. Exercise 7: Remove directory (rmdir)
 * rmdir (dir) to remove

8. Exercise 8: Moving Around (pushd, popd)
 * 'pushd' takes current directory and pushes into a list for later, changes it to another directory
		- 'save where I am, then go here'
 * 'popd' takes last directory you pushed and 'pops' it off, taking you back there
 * Doesn't work in powershell

9. Exercise 9: Making Empty Files (Touch, New-Item (windows))
 * Example on Windows
  - New-Item example.txt -type file

10. Exercise 10: Copy a File (cp)
	* cp (doc to copy) (name of copy)

11. Exercise 11: Moving a File (mv)
	* Moving (renaming files)

12. Exercise 12: View a File (less, MORE)
	* less for linux and more for windows

13. Exercise 13: Stream a File (cat)
	* Cat displays all of a file

14. Exercise 14: Removing a File (rm)
	* Have to delete all files within a directory to remove it

15. Exercise 15: Exiting Your Terminal (exit)
	* Exit is your friend

# General Notes
	* -r recurssively edits directories, manipulating all internal files within
