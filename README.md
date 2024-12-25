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
- `!help` - Shows this message.
- `!startup` - Adds the file to startup.
- `!exit` - Stops the RAT from working.
- `!usagelist` - Returns a list of active users.
- `!admin_check` - Checks if you have admin privileges on the target computer.
- `!bypass_uac` - Attempts to bypass UAC for admin privileges.
- `!shell` - Run a shell command.

### Surveillance Commands
- `!screenshot` - Sends a screenshot of the target machine.
- `!idletime` - Displays how long the user has been AFK.
- `!webcam_capture` - Captures a picture from the webcam.
- `!tasklist` - Returns a list of active tasks.

### File Management Commands
- `!chdir` - Changes the current directory. Use `!chdir <..>` to go back one directory.
- `!chdisk` - Changes the current disk (e.g., `E`, `C`, `D`).
- `!ls` - Displays all items in the current directory.
- `!download` - Downloads a file from the specified path.
- `!upload` - Uploads a file to the specified path.
- `!taskkill` - Kills the specified task.
- `!startfile` - Starts a file.
- `!delfile` - Deletes a file.
- `!hidefile` / `!unhidefile` - Hides/unhides a file.

### Information Gathering Commands
- `!whois` - Prints the user’s name.
- `!getip` - Gets the current user's IP address.
- `!clipboard` - Returns the user's clipboard content.
- `!stealpasswords` - Steals all the passwords from the device.
- `!grabroblox` - Grabs the user's Roblox account cookie.
- `!hardware_list` - Lists the user's hardware on newlines.
- `!grabdiscord` - Fetches the user's Discord account token.

### Sanctioning Commands
- `!bsod` - Blue screens the computer.
- `!disabletaskmgr` / `!enabletaskmanager` - Disables/enables Task Manager.
- `!logoff` - Logs the user off.
- `!shutdown` - Shuts the user's PC off.
- `!restart` - Restarts the user's PC.
- `!blockscreen` - Blocks the user's screen (irreversible until restart).
- `!critproc` - Makes the RAT a critical process (if terminated, causes BSOD).
- `!screenflip` - Rotates the user's screen 90 degrees.

### Fun Commands
- `!write` - Writes a sentence and presses Enter.
- `!setclipboard` - Sets the clipboard to the specified string of text.
- `!forcedesktop` - Forces the user to the desktop automatically.
- `!messmouse` - Shakes the user's cursor; run the command again to stop.
- `!opensite` - Opens a site on the user's browser.
- `!key_press` - Presses a specified key.
- `!showtaskbar` / `!hidetaskbar` - Shows/hides the taskbar.

### Communication Commands
- `!questionmsg` - Sends the user a question message.
- `!warningmsg` - Sends the user a warning message.
- `!errormsg` - Sends the user an error message.
- `!infomsg` - Sends the user an informational message.

---

### Disclaimer
This tool is intended for educational purposes only. Use responsibly and ensure compliance with all applicable laws and regulations.
