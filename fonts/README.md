# nerd patched fonts
The folder ttf_files/ contains ttf files that need to be placed under
~/.fonts folder.

then to update the font to the system the following command has to be run
> fc-cache -vf

These are nerd patched font files of SourceCodePro and Dejavu Sans family
obtained from https://github.com/ryanoasis/nerd-fonts

the repository is huge, hence needed font files were obtained using
git sparse-checkout option.


SourceCodePro font was used in the gnome-terminal that being compatible
with ranger and tmux for the icons
