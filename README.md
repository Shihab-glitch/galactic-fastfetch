# galactic-fastfetch
A fastfetch theme for the lovers of Galactic Adventures.
# Screenshots

<img src="preview/config_01.png" width="49%" align="left" />
<img src="https://upload.wikimedia.org/wikipedia/commons/2/24/Transparent_Square_Tiles_Texture.png" width="49%" height="16px" align="left" />
<img src="preview/config_02.png" width="49%" align="top" />

# Steps for KDE Arch (Other distros using KDE should also be the same)
1. Install 'fastfetch' in your machine / OS.
2. Generate config file by using command - $ fastfetch --gen-config
3. Install Nerd Fonts and change the Terminal Font to the installed Nerd Font of your liking. I use Meslo myself.
4. Locate your fastfetch config folder and copy the files of this repo into that folder. Replace the previous config.jsonc with mine.
5. If you have a KDE machine this will be enough.

# For Other OS / DE / WM :
1. "source": "$(find \"${XDG_CONFIG_HOME:-$HOME/.config}/fastfetch/pngs/\" -name \"*.png\" | sort -R | head -1)" change the line based on your directory to load the .png images.

# I am new to Github. If there is any problem in this repo, steps or anything else, you are free to correct me.
