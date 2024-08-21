
# Basic Linux Commands

## ls
- `ls`: Lists directory contents.
- Usage: `ls [options] [directory]`
- Example: `ls -l /home/user`

## cd
- `cd`: Changes the current directory.
- Usage: `cd [directory]`
- Example: `cd /home/user`

## pwd
- `pwd`: Prints the current working directory.
- Usage: `pwd`
- Example: `pwd`

## cp
- `cp`: Copies files and directories.
- Usage: `cp [options] source destination`
- Example: `cp file1.txt /home/user/`

## mv
- `mv`: Moves/renames files and directories.
- Usage: `mv [options] source destination`
- Example: `mv oldname.txt newname.txt`

## rm
- `rm`: Removes files or directories.
- Usage: `rm [options] file`
- Example: `rm file1.txt`

## mkdir
- `mkdir`: Creates directories.
- Usage: `mkdir [options] directory`
- Example: `mkdir new_directory`

## rmdir
- `rmdir`: Removes empty directories.
- Usage: `rmdir [options] directory`
- Example: `rmdir old_directory`

## touch
- `touch`: Creates an empty file or updates the timestamp of an existing file.
- Usage: `touch [options] file`
- Example: `touch newfile.txt`

## chmod
- `chmod`: Changes file permissions.
- Usage: `chmod [options] mode file`
- Example: `chmod 755 script.sh`

## chown
- `chown`: Changes file owner and group.
- Usage: `chown [options] owner[:group] file`
- Example: `chown user:group file1.txt`

## df
- `df`: Displays disk space usage.
- Usage: `df [options] [file]`
- Example: `df -h`

## du
- `du`: Displays disk usage of files and directories.
- Usage: `du [options] [file]`
- Example: `du -sh /home/user/*`

## ps
- `ps`: Displays information about running processes.
- Usage: `ps [options]`
- Example: `ps aux`

## kill
- `kill`: Sends a signal to a process.
- Usage: `kill [options] pid`
- Example: `kill -9 1234`

## top
- `top`: Displays real-time system information.
- Usage: `top`

## man
- `man`: Displays the manual for a command.
- Usage: `man [command]`
- Example: `man ls`

## echo
- `echo`: Displays a line of text.
- Usage: `echo [options] [string]`
- Example: `echo "Hello, World!"`

## cat
- `cat`: Concatenates and displays file contents.
- Usage: `cat [options] file`
- Example: `cat file1.txt`

## grep
- `grep`: Searches for patterns in files.
- Usage: `grep [options] pattern [file]`
- Example: `grep "search_term" file1.txt`

## find
- `find`: Searches for files and directories in a directory hierarchy.
- Usage: `find [options] [path] [expression]`
- Example: `find /home/user -name "*.txt"`

## wget
- `wget`: Downloads files from the internet.
- Usage: `wget [options] [url]`
- Example: `wget http://example.com/file.zip`

## curl
- `curl`: Transfers data from or to a server.
- Usage: `curl [options] [url]`
- Example: `curl http://example.com`

## sudo
- `sudo`: Executes a command as another user (usually root).
- Usage: `sudo [command]`
- Example: `sudo apt-get update`
