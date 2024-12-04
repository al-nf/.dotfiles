# info  
branch `zeus`: arch hyprland kitty ohmyzsh nvim  
i5-10400, 32gb ddr4, rx6400  
branch `babylon`: macOS yabai wezterm ohmyzsh nvim  
m3 air  
branch `halicarnassus`: arch i3 alacritty ohmyzsh nvim  
mbp retina 2015  

`sudo pacman -S --needed $(comm -12 <(pacman -Slq | sort) <(sort ~/.config/pkglist.txt))`
