# WCAT
WCAT COMMANDS
It is used to display or make a copy content of one or more files in the terminal.


## Usage
To displays content of the file in the terminal 
```bash
wcat.js filepath
```

To displays content of all files in the terminal in (contactinated form) in the given order. 
```bash
wcat.js filepath1 filepath2 filepath3...
```

To remove the spaces from the file, if that contains more spaces.
You can give any number of files

```bash
wcat -s file_names
```

To give numbers on the beginning of every line

```bash
wcat -n file_names
```

To remove the spaces present in the file, and give numbers in the begginning of every line after removing the spaces

```bash
wcat -b file_names
```

To replace the file content with the content of other files

```bash
wcat source_file_names > destination -file
```

To append the file content with the content of other files

```bash
wcat source_file_names >> destination -file
```

Reference link
https://www.tecmint.com/13-basic-cat-command-examples-in-linux/
