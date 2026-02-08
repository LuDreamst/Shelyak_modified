# Shelyak_modified
A conky widget based on [Shelyak](https://www.pling.com/p/1839849).
# Preview  
![](preview.png)  
# How to use?  
1. install conky and its dependencies   
   For apt usrs, you can run:  
   `
   sudo apt install conky-all lua5.4 curl playerctl
   `
2. make a dir named `conky`:  
   `mkdir -p ~/.config/conky`  
3. clone this repository and move it to `~/.config/conky`:  
   `git clone https://github.com/LuDreamst/Shelyak_modified.git && mv -v Shelyak_modified ~/.config/conky/`
4. Extract and install Abel.ttf from Abel.zip in the `fonts` folder.
   if necessary, try this to update the font cache:  
   `sudo fc-cache -v -f`  
5. change the [city_id](https://github.com/LuDreamst/Shelyak_modified/blob/main/scripts/weather-v2.0.sh#L9), [unit](https://github.com/LuDreamst/Shelyak_modified/edit/main/README.md#L16) in `scripts/weather-v2.0.sh` and [°C](https://github.com/LuDreamst/Shelyak_modified/blob/main/Shelyak-Dark.conf#L85) as your need.
6. Now you can go:
   `sh start.sh`
# Hope you enjoy it~
