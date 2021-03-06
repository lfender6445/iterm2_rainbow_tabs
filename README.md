# iTerm2 rainbow tabs

__randomized tab colors for iTerm2__

![iterm2 rainbow tabs](http://i.imgur.com/lAMHLEJ.png?4)

# install

```sh
mkdir ~/my_script_folder
cd ~/my_script_folder/
git clone git@github.com:lfender6445/iterm2_rainbow_tabs.git
cd iterm2_rainbow_tabs
chmod u+x iterm2_rainbow_tabs.sh
```
then add the following to your `~/.bash_profile` (bash) or ~ `/.zprofile (zsh)`

__dont forget__ to update the path so it points to the right file

```sh
if [ -f ~/my_script_folder/iterm2_rainbow_tabs/iterm2_rainbow_tabs.sh ];
 then . ~/my_script_folder/iterm2_rainbow_tabs/iterm2_rainbow_tabs.sh
fi
```

start a new terminal session or open a new tab. enjoy!

# modifying the colors

you can source the file to run any of the functions defined within `~/my_script_folder/iterm2_rainbow_tabs/iterm2_rainbow_tabs.sh`

eg `source ./iterm2_rainbow_tabs/iterm2_rainbow_tabs.sh`

then call `tab_orange_red` from command line to try out different colors!

if there is a color you dont like, you can remove it from the array `my_favorite_colors` defined at the bottom the script.

# misc
over 100 free [iTerm2 color schemes](https://github.com/mbadolato/iTerm2-Color-Schemes)

# thanks
https://github.com/jacaetevha/finna-be-octo-hipster/

