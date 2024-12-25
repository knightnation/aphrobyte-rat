# RAT Features and Commands

## Current Features

### Modules
- **Surveillance Modules**: Monitor the infected user.
- **Fun Modules**: Interact playfully with the target machine.
- **Sanctioning**: Apply restrictions or penalties.
- **Communication**: Chat with the infected user.
- **Multiple Agent Handling**: Manage multiple users simultaneously.
- **Persistence**: Ensure the RAT remains active.
- **File Management Modules**: Control files on the target machine.
- **Information Gathering**: Collect details about the target.
- **Undetected by Antivirus**: *(Currently detectable)*.

## Commands

### General Commands
- `!help (usage-id)` - Shows this message.
- `!startup (usage-id)` - Adds the file to startup.
- `!exit (usage-id)` - Stops the RAT from working.
- `!usagelist (usage-id)` - Returns a list of active users.
- `!admin_check (usage-id)` - Checks if you have admin privileges on the target computer.
- `!bypass_uac (usage-id)` - Attempts to bypass UAC for admin privileges.
- `!shell (usage-id) (command)` - Run a shell command.

### Surveillance Commands
- `!screenshot (usage-id)` - Sends a screenshot of the target machine.
- `!idletime (usage-id)` - Displays how long the user has been AFK.
- `!webcam_capture (usage-id)` - Captures a picture from the webcam.
- `!tasklist (usage-id)` - Returns a list of active tasks.

### File Management Commands
- `!chdir (usage-id) (path)` - Changes the current directory. Use `!chdir (usage-id) <..>` to go back one directory.
- `!chdisk (usage-id) (disk)` - Changes the current disk (e.g., `E`, `C`, `D`).
- `!ls (usage-id)` - Displays all items in the current directory.
- `!download (usage-id) (path)` - Downloads a file from the specified path.
- `!upload (usage-id) (path)` - Uploads a file to the specified path.
- `!taskkill (usage-id) (task)` - Kills the specified task.
- `!startfile (usage-id) (path)` - Starts a file.
- `!delfile (usage-id) (path)` - Deletes a file.
- `!hidefile (usage-id)` / `!unhidefile (usage-id)` - Hides/unhides a file.

### Information Gathering Commands
- `!whois (usage-id)` - Prints the user’s name.
- `!getip (usage-id)` - Gets the current user's IP address.
- `!clipboard (usage-id)` - Returns the user's clipboard content.
- `!stealpasswords (usage-id)` - Steals all the passwords from the device.
- `!grabroblox (usage-id)` - Grabs the user's Roblox account cookie.
- `!hardware_list (usage-id)` - Lists the user's hardware on newlines.
- `!grabdiscord (usage-id)` - Fetches the user's Discord account token.

### Sanctioning Commands
- `!bsod (usage-id)` - Blue screens the computer.
- `!disabletaskmgr (usage-id)` / `!enabletaskmanager (usage-id)` - Disables/enables Task Manager.
- `!logoff (usage-id)` - Logs the user off.
- `!shutdown (usage-id)` - Shuts the user's PC off.
- `!restart (usage-id)` - Restarts the user's PC.
- `!blockscreen (usage-id)` - Blocks the user's screen (irreversible until restart).
- `!critproc (usage-id)` - Makes the RAT a critical process (if terminated, causes BSOD).
- `!screenflip (usage-id)` - Rotates the user's screen 90 degrees.

### Fun Commands
- `!write (usage-id) (sentence)` - Writes a sentence and presses Enter.
- `!setclipboard (usage-id) (text)` - Sets the clipboard to the specified string of text.
- `!forcedesktop (usage-id)` - Forces the user to the desktop automatically.
- `!messmouse (usage-id)` - Shakes the user's cursor; run the command again to stop.
- `!opensite (usage-id) (url)` - Opens a site on the user's browser.
- `!key_press (usage-id) (key)` - Presses a specified key.
- `!showtaskbar (usage-id)` / `!hidetaskbar (usage-id)` - Shows/hides the taskbar.

### Communication Commands
- `!questionmsg (usage-id) (message)` - Sends the user a question message.
- `!warningmsg (usage-id) (message)` - Sends the user a warning message.
- `!errormsg (usage-id) (message)` - Sends the user an error message.
- `!infomsg (usage-id) (message)` - Sends the user an informational message.

---

### Disclaimer
This tool is intended for educational purposes only. Use responsibly and ensure compliance with all applicable laws and regulations.
