# AddToPath Win 10
Adds an "Add To Path" context-menu entry without installing any third party software or resources.

### Manual equivalent
"Control Panel" -> "System and Security" -> "System" -> "Advanced system settings" -> "Advanced" -> "Environment Variables" -> "User variables for \<Username\>" -> Double click on "Path" or create new "Path" -> Add folder paths of executables you want to be able to access fromn anywhere

### Properties:
- Creates "Path" if not existing already
- Adds folder-paths to Path variable of your user, not system-wide
- No duplicates when adding
- Supports multi-selection
- Doesn't need admin rights
- Optional console output about actions
- Also works with network locations (testeed on SMB, e.g. \\\\NasServer\some_dir)

### Variants:
 - Silent: Adding a folder happens silently (a powershell windows pops up very quick but closes immediately)
 - Normal: Adding a folder gives you a text Output of what happened and which Folder was added 
 
### Preview: 
![Alt Text](Preview.gif)
