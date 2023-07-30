# Universal Animation Detector

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
getgenv().Animations = { -- Example
     "69", -- Same as "M1".
     "M1", -- Same as "69".
}
   ```
