
a minimap works fine with 0r-hud 
- abdel4999 : retextured
- BuddyBoyVilla : first changes
> # Original map

https://www.gta5-mods.com/misc/atlas-colored-map-16k-that-also-works-in-radar

> **Info**

Retextured by abdel4999

> **Preview** / Textures :
![minimap_sea_0_0](https://github.com/AbdeLhere/fivem-redminimap/assets/140607607/22cdfa52-0843-4ec5-bdc2-eb7146285775)
- and more
> # Installation

# 1 ADD .lua file in fxmanifest.lua

 Go to 0r-hud/fxmanifest.lua and add 

```lua
 "client/minimap.lua"
```
in ```client_scripts {}```
![image](https://github.com/AbdeLhere/fivem-redminimap/assets/140607607/ce258ee8-dbaa-4328-b5c6-9bab185dc478)
Like That
```lua
client_scripts {
    "client/utils.lua",
    "client/variables.lua",
    "client/functions.lua",
    "client/events.lua",
    "client/nui.lua",
    "client/threads.lua",
    "client/commands.lua",
    "client/minimap.lua" -- < < < here is
}
```

 # 2 Add .lua File

drag "minimap.lua" file from "abl-redminimap/lua folder and drop it in "0r-hud"/"client" folder
- ![example](https://github.com/AbdeLhere/fivem-redminimap/assets/140607607/f0510503-a1d6-472a-a30b-67eb4e13b33e)

 # 3 Add Stream Folder

drag "stream" folder  from "abl-redminimap"/"STREAMASSESTS"/"stream" folder and drop it in "0r-hud" folder
- ![image](https://github.com/AbdeLhere/fivem-redminimap/assets/140607607/55ad9d09-4afa-467c-b4d5-6a6104389837)

)


 # 4 Fix Bugs

a -  Open "Visual Studio Code" 
b -  press "CTRL + K + O"
c -  Select you server folder Press "open"
d -  press <CTRL + SHIFT + F> 
e -  Search For " SetMapZoomDataLevel , SetRadarZoom , SetRadarAsInteriorThisFrame  "  And remove them
> Note : "Dont remove them from "0r-hud"/"client"/"minimap.lua"

- Search in your server SetMapZoomDataLevel, SetRadarZoom, SetRadarAsInteriorThisFrame and remove them , <Dont remove them from <"0r-hud"/"client"/"minimap.lua">

> # cayo minimap

<go to > "0r-hud"/"client"/"minimap.lua" <and set>  

```lua
local cayopericoactive = true -- false if no
```


# Enjooy ❤



Note : Dont give texture support / do it you're seld 
