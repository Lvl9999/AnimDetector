# Universal Animation Detector

# Main Source
```lua
--[[ Made by ThroughTheFireAndFlames#9925

    |  Universal Animation Detector

--]]
-- Note: It is meant to make auto dodge/parry/block scripts!

getgenv().Keybind = Enum.KeyCode.V

getgenv().Mag = 10

getgenv().Animations = { -- Animation ID | Animation Name
     "Anim1",
     "Anim2",
     "Anim3",
     "Anim4",
}

getgenv().Reaction = function()
    print("Animation Detected!");
end

loadstring(game:HttpGet("https://raw.githubusercontent.com/Lvl9999/AnimDetector/main/Universal"))();
```

# How to use:
1. Run this code.
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/CenteredSniper/Kenzen/master/AnimationStealer.lua"))();
```
2. Perform an "Attack", You will see that something added in the GUI.
  
3. Click on the name of the attack that added after you just attacked [It will be pasted to your clipboard]

4. Paste either the "ID" or "Name" to:

Example: Animation ID: "69" | Animation Name: "M1".

```lua
getgenv().Animations = {
     "69", -- Same as "M1".
     "M1", -- Same as "69".
  -- Add more animations here
}
   ```
5. Run the code
