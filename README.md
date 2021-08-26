# Mac-cli-Essentials
# Shortcuts
Command | Action
------------ | -------------
Tab | Auto-complete file and folder names
Ctrl + A	| Go to the beginning of the line you're currently typing on
Ctrl + E	| Go to the end of the line you're currently typing on
Ctrl + U	| Clear the line before the cursor
Ctrl + K	| Clear the line after the cursor
Ctrl + W	| Delete the word before the cursor
Ctrl + T	| Swap the last two characters before the cursor
Esc + T	  | Swap the last two words before the cursor
Ctrl + L	| Clear the screen
Ctrl + C	| Kill whatever you're running
Ctrl + D	| Exit the current shell
Option + →	| Move cursor one word forward
Option + ←	| Move cursor one word backward
Ctrl + F	  | Move cursor one character forward
Ctrl + B	  | Move cursor one character backward
Ctrl + Y	  | Paste whatever was cut by the last command
Ctrl + Z	  | Puts whatever you're running into a suspended background process
Ctrl + _	  | Undo the last command

# Basics
Command | Action
------------ | -------------
/ (Forward Slash) |	Top level directory
. (Single Period)	| Current directory
.. (Double Period)	| Parent directory
~ (Tilde)	| Home directory
sudo [command]	| Run command with the security privileges of the super user
nano [file]	 | Opens the Terminal editor
open [file]	 | Opens a file
[command] -h	| Get help about a command
man [command]	 | Show the help manual of the command

# Change Directory
Command | Action
------------ | -------------
cd	| Home directory
cd [folder]	| Change directory, e.g. cd Documents
cd ~	| Home directory
cd/	| Root of the drive
cd -	| Previous directory or folder you last browsed
pwd	| Show your working directory
cd..	| Move up to the parent directory
cd../..	| Move up two levels

# List Directory Contents
Command | Action
------------ | -------------
ls	| Display the name of files and subdirectories in the directory
ls -C	| Force multi-column output of the listing
ls -a	| List all entries including those with .(period) and ..(double period)
ls -1	| Output the list of files in one entry per line format
ls -F	| Display a / (slash) immediately after each path that is a directory, * (asterisk) after executable programs or scripts, and @ after a symbolic link
ls -S	| Sort files or entries by size
ls -l	| List in a long format. Includes file mode, owner and group name, date and time file was modified, pathname, and more
ls -lt	| List the files sorted by time modified (most recent first)
ls -lh	| Long listing with human readable file sizes in KB, MB, or GB
ls -lo	| List the file names with size, owner, and flags
ls -la	| List detailed directory contents, including hidden files

# File Size and Disk Space
Command | Action
------------ | -------------
du	| List usage for each subdirectory and its contents
du -sh [folder]	| Human readable output of all files in a directory
du -s	| Display an entry for each specified file
du -sk* or sort -nr	| List files and folders, totaling the size including the subfolders. Replace sk* with sm* to list directories in MB
df -h	| Calculate your system's free disk space
df -H	| Calculate free disk space in powers of 1,000 (as opposed to 1,024)

# File and Directory Management
Command | Action
------------ | -------------
mkdir <dir>	| Create new folder named <dir>
mkdir -p <dir>/<dir>	| Create nested folders
mkdir <dir1> <dir2> <dir3>	| Create several folders at once
mkdir "<dir>"	| Create a folder with a space in the filename
rmdir <dir>	| Delete a folder (only works on empty folders)
rm -R <dir>	| Delete a folder and its contents
touch <file>	| Create a new file without any extension
cp <file> <dir>	| Copy a file to the folder
cp <file> <newfile>	| Copy a file to the current folder
cp <file>~/<dir>/<newfile>	| Copy a file to the folder and rename the copied file
cp -R <dir> <"new dir">	| Copy a folder to a new folder with spaces in the filename
cp -i <file><dir>	| Prompts you before copying a file with a warning overwrite message
cp <file1> <file2> <file3>/Users/<dir>	| Copy multiple files to a folder
rm <file>	| Delete a file (This deletes the file permanently; use with caution.)
rm -i <file>	| Delete a file only when you give confirmation
rm -f <file>	| Force removal without confirmation
rm <file1> <file2> <file3>	| Delete multiple files without any confirmation
mv <file> <newfilename>	| Move/rename
mv <file> <dir>	| Move a file to the folder, possibly by overwriting an existing file
mv -i <file> <dir>	| Optional -i flag to warn you before overwriting the file
mv *.png ~/<dir>	| Move all PNG files from current folder to a different folder

# Command History
  Command | Action
------------ | -------------
  Ctrl + R	| Search through previously used commands
history n	| Shows the previous commands you've typed. Add a number to limit to the last n items
![value]	| Execute the last command typed that starts with a value
!!	| Execute the last command typed


   
