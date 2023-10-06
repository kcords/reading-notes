### Terminal notes

- A command prompt typically starts with the command, followed by arguments with options first (prefixed by a `-`)
  - Typically, following the command entry, an output response is displayed then the terminal returns to a new prompt
- BASH is one of the most common shells
- You can press ⬆️ or ⬇️ to cycle through previously entered commands
-

### Common commands
- `pwd` - print working directory shows the current directory you are currently located in
- `ls` - lists the contents of the current directory
  - `-l` long listing arg provides additional details
  - `-a` all files, including hidden
- `cd` -change directory
  - `~` references the home directory
  - `.` references the current directory
  - `..` references the parent directory
- `man <command>` brings up manual pages for a command to provide add'l details
  - `-k <searchterm>` searches for commands within the manual pages
  - `/<term>` searches for term within a manual page
- `mkdir` creates a new directory
  - `-p` tells it to create new parent directories (e.g. `parent1/parent2/child`)
  - `-v` outputs what the system is doing as the command runs
- `rmdir` removes a directory
- `rm` removes files and non-empty directories
  - `-r` recursive on child files and directories
  - `-i` interactive
  - `-f` force running of command ignoring warnings

### Filesystem
- Everything, including directories, are files
- File types are determined by file contents, not extensions
- File names are case sensitive and can have multiples with the same name, but different case configurations
- File names can have spaces, but must be enclosed in quotes or have the space escaped with a `\`
- Files prefixed with a `.` are automatically hidden

### References
- [Linux Tutorial - Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)