# OSEG (Open Source Event Graphics)

## Purpose
1. To provide a easy tool to create dynamic graphic package for live events & broadcast productions of any size.
2. To provide a standard format for dynamic graphics.
3. To provide a single file for all the hot swapable graphics.

## Defination
OSEG contains a package and individual graphics within the package. 

Standard Format:
`
{
title: "Test PCG",
graphics: [
 {
 title: "Main Graphic"
  [
  type: "box",
  x: 10, // any value from 0% - 100% of screen width
  y: 10, // any value from 0% - 100% of screen height
  width: 20, // any value from 0% - 100% of screen width
  heigh: 10, // any value from 0% - 100% of screen height
  color: "{global:exampleColor}" // could be a hex or dynamic variable
  ]
 }
]
}
`

## Note
The tool is planned to be used in 2021 for the live streaming platform SeasonCast (seasoncast.com)


