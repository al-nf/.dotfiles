# info  
branch `zeus`: arch hyprland kitty ohmyzsh nvim  
branch `babylon`: macOS wezterm ohmyzsh nvim  
branch `halicarnassus`: arch i3 alacritty ohmyzsh nvim

`sudo pacman -S --needed $(comm -12 <(pacman -Slq | sort) <(sort ~/.config/pkglist.txt))`
