# Iterm2 profile



### Settings
1. **To import the profile:** Profiles > {gear menu} > Import JSON profiles

1. **To show the terminal window:** Keys > Hotkey > Create a Dedicated Hotkey Window > {press CTRL+`}

1. **Add to .bash_profile:**
```
export PS1='\[\033[01;32m\]\u@\h\[\033[01;34m\] \w\[\033[31m\]$(__git_ps1 "(%s)")\[\033[01;34m\]$\[\033[00m\] '
```
