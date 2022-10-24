# Under Construction

|Work in progress|ToDo|
|:---:|:---|
|![Work_in_Progress](Images/work_in_progress.jpg)|- Update STLs to smaller v1.1 version<br>- Update CAD Images to smaller v1.1 version<br>- Update BOM to smaller v1.1 version<br>- Update changelog<br>- Delete this note :)|

<br>

# Filament Runout Sensor Housing
Sensor Housing for Generic CHN Filament Runout Sensor
<br><br>
![FS_Case_Drawing](Images/FS_Case_Drawing.png)
<br>
_**(image depreciated)**_
<br><br>
![Assembled_01](Images/Assembled_01.PNG)
<br>
![Sensor_Detail_01](Images/Sensor_Detail_01.jpg)
<br><br>

# Cover Options
|filamentsensor_cover.stl|filamentsensor_cover_logo-rotated.stl|filamentsensor_cover_nologo.stl|
|---|---|---|
| ![Cover_01](Images/Cover_01.PNG) | ![Cover_02](Images/Cover_02.PNG) | ![Cover_03](Images/Cover_03.PNG) |

_**(section depreciated)**_
<br>

# BOM
|Size|Qty|
|---|:---:|
|M3 heat set inserts|6|
|M3x **??** BHSC|4|
|M3x **??** SHCS (or BHSC)|2|
|M3x **??** SHSC (or BHSC)|2|
|M10 4mm OD tube connector|2|
|M3 T-Nut|2|

_**(section depreciated)**_
<br>

# Config
Add the following code to your **printer.cfg**
<br>
```
[filament_switch_sensor filament_runout]
pause_on_runout: True
event_delay: 3.0
pause_delay: 0.5
switch_pin: <your pin>
#runout_gcode:
#insert_gcode:
```

# Compatibility

|V0|V1.8|V2.4|VSW|Trident|
|:---:|:---:|:---:|:---:|:---:|
| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |

<br>

# Changelog
v1.0 (21.10.2022) - Release
<br>
