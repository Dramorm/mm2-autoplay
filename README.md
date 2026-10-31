# MM2 Autoplay

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Dramorm/mm2-autoplay/refs/heads/main/main.lua"))()
```

MM2 Autoplay is an AI-style Roblox automation script for Murder Mystery 2. Unlike basic autofarms that repeatedly follow fixed paths, it evaluates routes, reacts to threats, adapts to roles, detects ladders, recovers from stuck situations, and makes movement decisions dynamically.

## Features

- Smooth Roblox pathfinding with jump-point handling
- Ladder and truss detection
- Coin routing and path planning
- Innocent, Sheriff, Murderer, Survivor, and Zombie behavior settings
- Bag-full actions and role-specific reset options
- Evasion and stuck recovery
- Optional key system with no IP check
- Discord webhook status reports
- Configurable overlays, logs, watchdog, and server hopping

## Auto-execute

Put the loadstring in your executor’s **auto-execute / autoexec** folder or auto-execute script. This is required so MM2 Autoplay starts automatically when Roblox launches or joins the game.

After it runs:

1. Complete or skip the key prompt when it appears.
2. Use the **Home** tab for key status and general controls.
3. Use the role tabs to configure behavior.
4. Use the **Webhook** tab to configure Discord reporting.

The interface can be shown or hidden with the configured UI hotkey, which defaults to Right Shift.

## Key system

Key validation checks the Work.ink token response only. No IP lookup or IP matching is performed. The `bypass` value is accepted as a permanent local bypass.
