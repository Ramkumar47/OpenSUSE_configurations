# Gnome-terminal configuration
This directory contains the gnome-terminal profile files that can be loaded back
to the terminal configuration for restoring the profile.

the command used to dump the profiles is
'''
$ dconf dump /org/gnome/terminal/legacy/profile:/ > gnome-terminal-profiles.dconf
'''

and the command to be used to load the profiles is
'''
$ dconf load /org/gnome/terminal/legacy/profiles:/ < gnome-terminal-profiles.dconf
'''

the following is the reference used for this

https://unix.stackexchange.com/questions/448811/how-to-export-a-gnome-terminal-profile
