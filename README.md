# Roblox Unfocused Window Optimization
## Information

When the Roblox client is unfocused, this script will lower CPU & GPU usage therefore letting your PC rest.

The way this works is whenever the window is unfocused, 3D Object Rendering Functions are disabled and the FPS cap is set to 0 and when the window gets focused again, the 3D Object Rendering Functions will be re-enabled and the FPS cap will be set to infinity.

It is recommended that you put this script into your executor's **auto execute** *(autoexec)* folder.

#### You need the function `setfpscap(<uint> FPS Cap)` to run this script.

## Script
Load the script by copying it from [here](https://github.com/Exunys/Roblox-Unfocused-Window-Optimization/blob/main/Main.lua) or by executing the code below.

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/Roblox-Unfocused-Window-Optimization/main/Main.lua"))()
```
## Contact Information
- [Email](mailto:exunys@gmail.com)
- [Discord](https://discord.com/users/611111398818316309)
- [Roblox](https://www.roblox.com/users/330279990/profile)
