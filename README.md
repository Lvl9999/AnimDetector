# Universal Animation Detector
Script that allows you to detect animations fired within certain distance.

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
-----------------------------------------------------------------------------------------------------------
# Keybind
```lua
getgenv().Keybind = Enum.KeyCode.V -- In this case its "V" OFF|ON toggle.
```
# Distance
```lua
getgenv().Mag = 10 -- In this case it detect if someone is 10 studs near you.
```
-----------------------------------------------------------------------------------------------------------
# How to use:
1. Run this code.
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/CenteredSniper/Kenzen/master/AnimationStealer.lua"))();
```
2. Perform an "Attack", You will see that something added in the GUI.
  
3. Click on the name of the attack that added after you just attacked [It will be pasted to your clipboard]

4. Paste either the "ID" or "Name" to the "Animations" table variable:
----------------------------------------------------------------------
  Example: Animation ID: "69" | Animation Name: "M1".

```lua
getgenv().Animations = {
     "69", -- Same as "M1".
     "M1", -- Same as "69".
  -- Add more animations here
}
   ```
# Manage your reaction
Here's how you decide what to do when you detected an animation fired within "Mag" variable's value:

```lua
getgenv().Reaction = function()
    print("Animation Detected!"); -- In this case it will print the word "Animation Detected!" in F9 console
end
```

5. Run the "Main Source" with the edited changes.
