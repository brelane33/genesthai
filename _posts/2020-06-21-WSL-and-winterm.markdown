---
layout: single
title:  "WSL, Ubuntu, and Windows Terminal"
date:   2020-06-20 20:23:53 -0500
---

## WSL Woes

I've made amends with the fact that I will be coding on Windows
until I get rich and I can afford a MacBook. I have an Air but it's
not easy to use unless hooked up to a monitor

I was struggling yesterday with Windows Terminal having a lot of graphical issues.
On my desktop I have a GSync monitor. Apparently this makes the terminal freak out,
because they hadn't been testing with it. The FPS would drop down to 48~ when focused.

On their experimental branch they rolled out `v0.11.1333.0` that fixed this with this
global setting: 

`experimental.rendering.software` 

and in their most recent Preview release, `v1.1.1671.0`, they finally added
support for raw modifier keys that fixed many issues for Vim and bash. Thank God.

# I can't believe it's not linux! 

Using the raspberry scheme they provided, with these updates, WSL 2, and Ubuntu 20...
I can trick myself into thinking I'm using Linux enough to be somewhat productive.

Hallelujah.

I was struggling with so many other things in basic setup just trying to get a comfy
IDE setup it was blocking me from actually producing anything. Anyone else ever run into that?

My WSL setup looks like this:

```
    {

    "defaultProfile": "{07b52e3e-de2c-5db4-bd2d-ba144ed6c273}",

    "experimental.rendering.software": true,

    "copyOnSelect": false,

    "copyFormatting": false,

    "profiles":
    {
        "defaults":
        {
        },
        "list":
        [
            {
                "guid": "{07b52e3e-de2c-5db4-bd2d-ba144ed6c273}",
                "hidden": false,
                "name": "Ubuntu-20.04",
                "colorScheme" : "Raspberry",
                "cursorColor" : "#FFFFFF",
                "padding" : "5, 5, 5, 5",
                "fontFace" : "Cascadia Code",
                "tabTitle": "Ubuntu",
                "source": "Windows.Terminal.Wsl"
            },
            {
                "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
                "hidden": false,
                "name": "Azure Cloud Shell",
                "source": "Windows.Terminal.Azure"
            }
        ]
    },

    "schemes": [
    {
                "name" : "Raspberry",
                "background" : "#3C0315",
                "black" : "#282A2E",
                "blue" : "#0170C5",
                "brightBlack" : "#676E7A",
                "brightBlue" : "#80c8ff",
                "brightCyan" : "#8ABEB7",
                "brightGreen" : "#B5D680",
                "brightPurple" : "#AC79BB",
                "brightRed" : "#BD6D85",
                "brightWhite" : "#FFFFFD",
                "brightYellow" : "#FFFD76",
                "cyan" : "#3F8D83",
                "foreground" : "#FFFFFD",
                "green" : "#76AB23",
                "purple" : "#7D498F",
                "red" : "#BD0940",
                "white" : "#FFFFFD",
                "yellow" : "#E0DE48"
      }
    ]

}
```


# AWS Amplify

I got this crap up and running, finally, on Amplify, got my domain registered. Super easy setup. 10/10

I tried using the github-pages gem but the version of the gem hadn't matched up with Jekyll. Not wanting to
spend any more time on setting things up I just ponied up some money, and I'm glad I did.

Amplify gives you the ability to add free domains to your page so you can develop on multiple branches,
a feature I imagine is useful for getting your ideas on paper before pushing to master. If you couldn't tell I don't really give a crap about that. I'm totally ok with word vomitting from my brain and making it available to the general public.

As I get more familiar with this setup I'll dive into the more advanced features, which I'm excited to check out.



