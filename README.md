# kebab

## Overview
- recursively change snake case directories and/or filenames to kebab case
- will preserve first character if it's an underscore (often used to ensure file/dir is top of dir tree)

```bash
Version 1.0.0

Usage: kebab [option] ...

Options:
  --dir        Rename directories with snake_case names to kebab_case.
  --files      Rename files with snake_case names to kebab_case.
  --all        Rename both directories and files with snake_case names to kebab_case.
  --empty      Find empty directories.
  --delete     Find and delete empty directories (use with --empty).
  --help       Display this help message.
  --version    Display version (1.0.0).


# Examples
# an_example_dir -> an-example-dir
# an_example_file.md -> an-example-file.md
```

## Install
Download/clone and add cloned repo location to PATH as you normally would for you shell or OS distribution.

```bash
# edit file
vim ~/.bash_profile
vim ~/.bashrc

# add path
export PATH="$PATH:/path/to/script/directory"
export PATH="$PATH:/Users/adriangoodyer/src/adegoodyer/kebab"

# dot source
source ~/.bashrc  # If you added the line to ~/.bashrc
source ~/.bash_profile  # If you added the line to ~/.bash_profile
```

> Instructions are for vim/bash, feel free to add your own and create a pull request.
