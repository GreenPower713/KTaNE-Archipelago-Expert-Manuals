# KTaNE Expert Manuals

This program contains all the manuals that are required to play archipelago. Rule seed is adapted to the correct AP Slot and is automatically applied. Please download the one that is the same as your OS.

You can download the APWorld needed for this at [this address](https://github.com/GreenPower713/Archipelago/releases).

The defuser client mod can be found on [Steam](https://store.steampowered.com/app/341800/Keep_Talking_and_Nobody_Explodes/). 
Please refer to the [Setup Guide](https://github.com/GreenPower713/Archipelago/blob/main/worlds/ktane/docs/setup_en.md) for all the needed information.

## FAQ
### I am on Linux. Why isn't there a version for me?
The Expert Manuals Client is the reason that Linux is currently not supported. The Linux version currently has some issues with this part in the connection. I have a hunch on where this issue might reside, but it would take a whole code refactoring to fix properly.

### I am on Linux. Can I play anyway?
Keep in mind that this game is currently not supported for Linux. However, the answer is yes, but it's a bit more tricky. You can download the windows version and use proton/wine to use it. But again, this is a workaround and is not currently supported for now. A full real release will have to happen before it is considered supported.

### Why doesn't the program work when I double click on it on MacOS?
As an alpha build, I didn't bundle it in an .app file. This means that I can't certify that it will work with a double-click; it might. If not, you can run it via a terminal by following these instructions.
1. Open a terminal
2. Use the "cd" command to change the working directory to the one containing the program.
3. Run ./KTaNEExpertManualsClient_mac

This should work. If you need assistance, feel free to ping me in the Discord thread.

### On MacOS, it gives me an error with "permission denied". Can I fix it?
Yes. If you get an error similar to this one, you can follow these instructions to fix your issues.
1. Open a terminal
2. Use the "cd" command to change the working directory to the one containing the program.
3. Run chmod +x KTaNEExpertManualsClient_mac

This should give the needed permissions for you to run this program. Again, if you need help, feel free to ask in the Discord thread.

### The manuals do not contain the same symbols as the bomb. What is happening?
First of all, make sure that you did install the [Rule Seed Modifier mod by samfundev](https://steamcommunity.com/sharedfiles/filedetails/?id=2037350348) as mentioned in the [Setup Guide](https://github.com/GreenPower713/Archipelago/blob/main/worlds/ktane/docs/setup_en.md). If you did and the manuals are still different, the problem is that the ruleseed has a way to randomize itself randomly for each bomb. Sadly, this is ran after Archipelago tries to change it to the one used in the Manuals. If this happens to you, you can follow these instructions to fix it:
1. Load into your AP save in-game
2. In the ruleseed settings, deselect the random rule seed.
3. Launch a mission ***from the missions folder, not from the AP mod***
4. Now try to launch a mission from the AP mod. Everything should work properly.

This should fix the issue. If you need help, you can ask in the Discord thread.
