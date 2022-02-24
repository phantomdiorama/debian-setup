### Map Caps Lock to Backspace

 1. Go to *Applications Menu* > *Settings* > *Session and Startup* >
    *Application Autostart*.
 2. Click *Add*.
 3. Enter the following fields.
      - Name: Uncap
      - Description: Map Caps Lock to Backspace
      - Command: `setxkbmap -option caps:backspace`
 4. Click *OK*. Click *Close*.

Log out and log into the desktop again to confirm

Reference: https://github.com/susam/dotfiles/blob/master/docs/debian-setup.md