# The Command Line Terminal
Before windows/macOS and the desktop, there was just the command line (or terminal; what hackers exaggeratedly use in movies). Though today's user interfaces are convenient and accessible, the terminal remains the most powerful method of interacting with your computer and code repositories.

Windows comes with `CMD.exe`, which used to be the default command prompt until Windows 10 and PowerShell. I recommend that you use PowerShell (the prompt with blue background lol) for this short tutorial. MacOS and Linux comes with a single terminal built in.

## Basic Commands
### Traversing the Filesystem
 - `ls`: List files/folders in the current folder/directory (`dir` on `CMD.exe`)
 - `pwd`: Get the current directory that the terminal is in
 - `cd folder_name`: ("change directory") enter into a folder directory
    - `cd folder_name/sub_folder` enter into a sub-folder (can cd in multiple levels)
 - `cd ..` or `cd ../..`: move one (two or more) directory(ies) out of the current one

### Creating/Deleting/Modifying Files
 - `touch file_name`: creates an empty new file with the file name (`$null >> file_name` for Windows)
 - `rm file_name`: *permanently* removes the specified file
 - `mv file_name another_file_name`: renames (technically moves) the current file to another file name (can be used to move a file to other directories)
 - `cp file_name another_file_name`: copies the current file to another file name

### Managing Directories
 - `mkdir directory_name`: make a new folder/directory with specified name
 - `rm -r directory_name`: removes a directory and its contents

### Misc
 - `clear`: clears the terminal output
 - `man terminal_command`: gives the reference of the said command
 