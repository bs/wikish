# Playing with MacOS Tiled WMs
> since I got an
[ultrawide](https://www.lg.com/us/monitors/lg-49WL95C-W-ultrawide-monitor)
monitor. I've had my doubts as last I looked they seemed to be pretty hacky.

## Initial research
People seem to be really into  
https://github.com/koekeishiya/yabai +_ https://github.com/koekeishiya/skhd

And also Phoenix  
https://github.com/fabiospampinato/phoenix - a good phoenix config


Downloaded Rectangle  
https://github.com/rxhanson/Rectangle  
Seems like a really easy to use spiritual successor to Spectacle


Hamerspoon is still around which is very cool. Here's an example config

```
fit2rule 3 months ago [–]

I'm using Hammerspoon on MaOS to give me a semi-tileable windows interface. Here is my config:

    local hyper = {"ctrl", "alt", "cmd"}

    hs.loadSpoon("MiroWindowsManager")

    hs.window.animationDuration = 0.3
    spoon.MiroWindowsManager:bindHotkeys({
      up = {hyper, "up"},
      right = {hyper, "right"},
      down = {hyper, "down"},
      left = {hyper, "left"},
      fullscreen = {hyper, "f"}
    })

    -- https://github.com/miromannino/miro-windows-manager

This allows me to place any MacOS window in either a horizontal or vertical third, or a quadrant, or a half, perfectly divided in such a way that I can maximise use of my screen while running multiple apps. My most common work environment is to have a terminal on one half of the screen, docs on the other - or two terms on top of each other on one side, docs on the other.

This is so useful for me that I yearn to make the same hotkeys work on my Linux machine, but I haven't worked out what window manager I want to use to do it .. probably Awesome of course, but I'd love to be able to use the same Hammerspoon scripts (Lua) somehow .. 
```

Also Hyperswitch (not sure what this is) w/ Hammerspoon?  

[Amethyst](https://ianyh.com/amethyst/) is still around.
