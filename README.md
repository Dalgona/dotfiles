# My .dotfiles

## Contents

- Startup scripts and configurations
- Vundle.vim (as a git submodule)
- Antigen
- A list of Visual Studio Code extensions
- An installer script

## Installing

### Requirements

- `git`, `curl`
    For proper operation of Vundle.vim
- Visual Studio Code
    Optional. Extensions installation will be skipped if not present.

1. Clone this repository.
2. Run the installation script `./install`.
    This script will...
    - Fetch all registered git submodules
    - Backup original files under the home directory (if any)
    - Make a symbolic link of each file or directory
    - Install Vim plugins using Vundle
    - Install extensions for Visual Studio Code (if possible)
3. Pray for good luck.

## Disclaimer

All files in this package comes WITHOUT ANY WARRANTY. I am not responsible for
any loss of your data caused by my stuffs. Use at YOUR OWN RISK.
