# galactic-fastfetch
A fastfetch theme for the lovers of Galactic Adventures.
# Screenshots

<img src="preview/config-02.png" width="49%" align="top" />

# Steps for setting this fastfetch config :
1. Install 'fastfetch' in your machine / OS.
2. Generate config file by using command - $ fastfetch --gen-config
3. Install Nerd Fonts and change the Terminal Font to the installed Nerd Font of your liking. I use Meslo.
4. Locate your fastfetch config folder and copy the files of this repo into that folder. Replace the previous config.jsonc with mine.

# Changes to load Custom .png images :
1. Change the USER ("source": "$(find "/home/USER/.config/fastfetch/" -name "*.png" | sort -R | head -1)") of the config for pngs to work.

