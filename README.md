# ANET_ET5_PRO_Klipper

```Issues and resolution```



```Input shaping installation```
https://www.klipper3d.org/Measuring_Resonances.html


TITAN EXTRUDER
https://github.com/Rat-Rig/v-core-3-klipper-config/blob/master/titan.cfg
https://github.com/doxxedd/KP3s_Klipper/blob/main/printer.cfg

Rotation distance
https://www.youtube.com/watch?v=5Suy_MGGFL4

If you're doing straight up measurements of your extruder putting out filament just ignore the gear_ratio setting, it won't make much of a difference, if any. It literally just multiplies your rotation_distance, nothing else. Unless there's some reason you can only measure before the reduction gears it's not necessary.

Unless you want to. Then by all means.

And rotation_distance can be calculated very easily and always should be done by the end user, not by anyone else's math. You might be using a different motor, bigger or smaller gears, etc. etc. Good howto in the Klipper docs here: https://www.klipper3d.org/Rotation_Distance.html


https://gagansharma18.github.io/ANET_ET5_PRO_Klipper/rotation_distance.html
