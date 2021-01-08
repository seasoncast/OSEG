# OSEG (Open Source Event Graphics)

## Purpose
1. To provide a easy tool to create dynamic graphic package for live events & broadcast productions of any size.
2. To provide a standard format for dynamic graphics.
3. To provide a single file for all the hot swapable graphics needed in a single event.

## Defination
OSEG contains a package and individual graphics within the package. There is also a runtime javascrpt script to pull data from any source that runs on a vm.

Standard Format:
```
{
   "title":"Example Package",
   "graphics":[
      {
         "title":"Main Graphic",
         "components":[
            {
               "type":"box",
               "x":10,
               "y":10,
               "width":20,
               "heigh":10,
               "color":"{global:exampleColor}"
            }
         ]
      }
   ]
}
```
x, y, width, height values are based on a percentage of the screen full size. Colors & text can be a hex or dynamic variable.

## Note
The tool & standard are planned to be used in 2021 for the live streaming platform SeasonCast (seasoncast.com)


