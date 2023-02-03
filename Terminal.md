- `rm` - remove files or directories
- `touch filename` - create a file
- `vim filename` - edit a file via Vim
    - `i` - used to enter input mode.
    - `l` - moves the cursor to the right.
    - `h` - moves the cursor to the left.
    - `k` - moves the cursor up.
    - `j` - moves the cursor down.
    - `w` - place cursor after a word
    - `b` - jump to beginning of a word
    - `dd` - delete a line
    - `u` - undo a command
    - `dw` - delete word where cursor is located
    - `esc` - enter command mode
    - `:wq` - save and quit vim
    - `.` (period) - repeat a previous command
- `ls` - list directory contents
    - `ls -a` - list all contents
- `mv src dir` - move src to directory
- `mv src dest` - rename src to destination
- `cp` - copy files or directories
- Number of arguments: `$#`
- All positional arguments (as a single word): `$*`
- All positional arguments (as separate strings): `$@`
- List array elements: `${array[*]}`
- `pwd` - present working directory
- `cd /` - root
- `cd ~` or `cd` or `cd $HOME` - home
- `grep [OPTION...] PATTERNS [FILE...]` - search and print lines that match patterns
- `man` - user manual for any command
- `find DIR -name PATTERN` - search for file in a directory hierarchy
- `chmod` - change/modify file permissions
- `sort file` - sort lines of text files
- `sudo` - runs commands as the root user
    - `apt` - CLI for managing packages
        - `install` - install a package
        - `update` - checks to see which packages can be updated.
        - `upgrade` - performs the update for packages that can be updated

- **Piping** (`|`) - take command and feed it to another
- **Redirection** (`>`) - write output to a file
    - e.g. `scoop list > scoop-installs.txt`