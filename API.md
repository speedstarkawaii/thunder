### Thunder `function` library

Here is how to use the `functions`:

```lua
info("Hello, World!") -- Pushes message onto console
-- This prints "Hello, World!" to the console as "information" also known as the "blue" print; however most modern exploits have deprecated this and may not exist on other exploits and it accepts any argument (string, integer, etc)


setclipboard(game.Workspace.Gravity) -- 196.2 should be on the clipboard
-- Sets data onto the clipboard, mostly used for setting links where the user can go to or for key systems


getclipboard() -- Returns the last data set on clipboard as a string


err("Script invalid! Join discord.gg/myscript") -- Pushes error onto console
-- Errors the message onto console, works differently as the error invokes from the print address rather then a script or "single lined error"


closerbx() -- Closes roblox
-- Terminates the roblox process; detaching thunder from roblox


is_thunder_func() -- Returns true
-- Returns true if it originated from thunder itself; useful for 'thunder' only scripts or validating your script so thunder can only support it


setscriptbytecode(game.MyModuleScript) -- Sets new script bytecode
-- Sets the bytecode of a ModuleScript and LocalScript; a Script will not be accepted
```
