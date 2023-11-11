# zmk_corne

This project would not be possible without the help of these people:
https://github.com/makgyber/kiai-split
https://github.com/wj-zhe/Kretstrad
or most importantly:
https://github.com/alexpantiukhin/zmk-config-xiao
This one helped me figure out the layout for the files i need to make the firmware compile. It is modified, but the core of this persons work is still there, so thanks.

But lets not forget the best layout for custom keyboards :)
https://github.com/foostan/crkbd

And also the youtubers who helped me understand:
https://www.youtube.com/@joe_scotto
https://www.youtube.com/@SethusBuilds
https://www.youtube.com/@BenVallacksKeyboards
https://www.youtube.com/@BenVallack

This corne like build features a Xiao BLE controller and a custom designed board designed by me, but heavily inspired by the crkbd.
The wiring based on how the kiai split does it to keep both controllers up side but not use multiple pads like the older cornes or the helix

KiCad project is a redesigned corne choc, but everything is changed except the general outline. Files in this repository

The PCB did work, but there is some clearance issues with the power switch and the controller, so that will be changed in the kicad folder.

battery test:
10 nov 22:53:31 L = 3,89V R = 3,89V
+ 10:45 (battery connected) =
11 nov 09:46:10 L = 3,85V R = 3,86V
+ 02:30 (youtube usage) =
11 nov 12:15:10 L = 3,84V R = 3,85V
+ 01:30 (youtube and 10 min osu) =
11 nov 13:42:30 L = 3,83V R = 3,84V
+ 00:00 (disconnect battery) =
11 nov 13:42:30 L = 3,83V R = 3,84V


avrg loss
  L = 0,004V/h
  R = 0,003V/h

estimated battery life (4,1V - 3,2V = 0,9V)
  L = 0,9V / 0,004V = 225h = 9 days
  R = 0,9V / 0,003V = 300h = 12 days