# command_cheatsheet

My macOS CLI cheatsheet.

## Setup Steps

### 1. Make symlink to home dir

```bash
# path/to/repo -> home dir
ln -s ~/dev/cheatsheets/command_cheatsheet/command_cheatsheet.txt ~/command_cheatsheet.txt
```

### 2. Make alias for command

```bash
vi ~/.zshrc

# In .zshrc
alias my_command_cheatsheet="cat ~/command_cheatsheet.txt"
```

## Helpful Tips

### 1. Grep for specific thing

```bash
my_command_cheatsheet | grep dns
```
