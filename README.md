# Laptopdots
![Screenshot](screenshot/screenshot.png)
My dotfiles for i3wm and sundry apps on my Laptop, extremely similar to my main dots with some customisation for monitor selection and some misc changes. Used on Manjaro so your mileage may vary on other distro's. (Although any arch based distro SHOULD work)

I use user templates for Pywal extremely heavily, In other words, many of the config files are actually in the ~/.config/wal/Templates folder. They need to be copied to the same folder on your system and once you've ran wal on a wallpaper you can then symlink them to their usual locations for them to work. 


# Applications Needed / Used 

- i3wm gapps 

- spotifyd and spotify-tui

- ranger 

- conky (Symlink from templates)

- Polybar

- Pywal (By far the most important, it is essential)

- wpgtk (Needed to theme gtk via pywal schemes) 

- dunst (Symlink dunstrc from templates)

- nitrogen (for wallpapers, you can also use feh but i3 config will need to be edited)

- st (I use a modified version of lukesmithxyz's @ https://github.com/asolopovas/st,
      any version will work just ensure it is compiled with xresource patch)

- zsh (Autocomplete and highlighting plugins used)

- Yay (not needed but manually building everythings a pain)

- lx-appearance (Not strictly needed but makes config abit easier on i3)

- Rofi (Symlink from Templates)

- vim (I would highly recomend taking a look at the following vim config,https://github.com/amix/vimrc its damn good and easy to install even for novice's)


I include a awesome application menu script written by https://github.com/Chrysostomus/ . All credit goes there!

Note that I predominantly use Hack Nerd Font so please make sure that is installed or
adjust accordingly (The fonts I use are included) 


