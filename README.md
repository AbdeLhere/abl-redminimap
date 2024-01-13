
a minimap works fine with 0r-hud 

> # Original map

https://www.gta5-mods.com/misc/atlas-colored-map-16k-that-also-works-in-radar

> **Info**

Retextured by abdel499

> **Preview**

![1](image-3.png)
![2](image.png)
![3](image-1.png)
- and more
> # Installation

> 1 , Go to 0r-hud/fxmanifest.lua and add 

```lua
 "client/minimap.lua"
```
in ```client_scripts {}```

- ![example](image-1.png)

- example 2
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

> 2 drag "minimap.lua" file from "abl-redminimap/lua folder and drop it in "0r-hud"/"client" folder
- ![example](image.png)


> 3 drag "stream" folder  from "abl-redminimap"/"STREAMASSESTS"/"stream" folder and drop it in "0r-hud" folder
- ![example](image-2.png)

> 4 


a/ Open <Visual Studio Code> 
b/ press <CTRL + K + O> 
c/ Select you server folder Press <open> 
d/ press <CTRL + SHIFT + F> 
e/ Search For <     SetMapZoomDataLevel / SetRadarZoom / SetRadarAsInteriorThisFrame      > <and remove them>
Note : <Dont remove them from <"0r-hud"/"client"/"minimap.lua">

- Search in your server SetMapZoomDataLevel, SetRadarZoom, SetRadarAsInteriorThisFrame and remove them , <Dont remove them from <"0r-hud"/"client"/"minimap.lua">

> # cayo minimap

<go to > "0r-hud"/"client"/"minimap.lua" <and set>  

```lua
local cayopericoactive = true -- false if no
```


# Enjooy ❤



