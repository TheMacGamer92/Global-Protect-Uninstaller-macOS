# Global-Protect-Uninstaller-macOS

This is a simple uninstaller for the macOS version of Global Protect. It simply calls the uninstall script bundled in the Global Protect app itself, but gives the user a simple password prompt instead of using terminal.

This is useful in the event of a broken install where a user cannot access a Self Service uninstaller.

This was created using script editor and is writtn with a combo of AppleScript and Bash. You can deploy this via Jamf or simply send it in an email if need be. 

This has been tested with Global Protect v5.2.10 to v6.1.2 on macOS11 to macOS14 with both Intel and Apple Silicon.
