# i3blocklet-pulseaudio
i3 blocket that shows that controls the volume using pulse audio
 

# Screenshots 

| Screenshot                        | Description  |
| --------------------------------- | -------------|
| ![mute](screenshots/mute.png)     | Shows when sink is mute, can be toggled with mouse right click button | 
| ![off](screenshots/off.png)       | Shows when volume is zero and is not mute     | 
| ![normal](screenshots/normal.png) | shows the volume percentage                   |  

# Block configuration


```sh

[i3blocklet-pulseaudio]
interval=once
signal=10
command=$GIT_PROJECT_ROOT/script

#fallback values of custom params right side is default parameter
step=5%  
rofi_theme=
rofi_window_anchor=
```