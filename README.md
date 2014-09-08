# What is this?

This is a repo of our user settings / key mappings for Sublime Text.

Each branch represents a different install (Home Mac, Work Mac etc).

Note that the `User` folder is ignored on master, as it is branch / install specific.


## Usage

Clone to the appropriate location (on a Mac this will be `~/Library/Application Support/Sublime Text 3/Packages`), or alternatively create a symlink to your Dropbox folder if you have it installed there:

    # symlink
    sudo ln -s /Users/j.darwin/Dropbox/Sublime/User /Users/j.darwin/Library/Application\ Support/Sublime\ Text\ 3/Packages

    # set permissions
    cd /Users/j.darwin/Library/Application\ Support/Sublime\ Text\ 3/Packages
    sudo chown -R j.darwin:"FFXNZ\Domain Users" User

Install package manager to install the packages speficied in the config: https://sublime.wbond.net/installation

If your sidebar is looking a little confused, it's probably because you haven't yet installed the theme package.
You can always revert to the default theme by using the following preference:

        "theme": "Default.sublime-theme",
