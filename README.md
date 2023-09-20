# kebab

## Overview
Recursively change snake case directories and/or filenames to kebab case.

```bash
Usage: kebab [-d] [-f] [-a]
  -d  Rename directories with snake_case names to kebab_case.
  -f  Rename files with snake_case names to kebab_case.
  -a  Rename both directories and files with snake_case names to kebab_case.

# Examples
# an_example_dir -> an-example-dir
# an_example_file.md -> an-example-file.md
```

## Install
Download/clone and add script to PATH as you normally would for you shell or OS distribution.

```bash
# edit file
vim ~/.bash_profile
vim ~/.bashrc

# add path
export PATH="$PATH:/path/to/script/directory"

# dot source
source ~/.bashrc  # If you added the line to ~/.bashrc
source ~/.bash_profile  # If you added the line to ~/.bash_profile
```

> Instructions are for vim/bash, feel free to add your own and create a pull request.
