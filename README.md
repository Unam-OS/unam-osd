# unam-osd
Small shell script and tint2 theme to simulate desktop OSD on lightweight window managers

## How to use
Copy the unam-osd script to `/usr/bin` (`sudo cp unam-osd /usr/bin`) and make shure to add execution privileges (`sudo chmod +x /usr/bin/unam-osd`)

To be able to hide/show tint2 on multiple keypresses, you will also have to make a file in `~/.config/unam/expo` named `running` (when launched, the script will store the tint2 instance's PID to kill it on 2nd launch)

Then copy the OSD.tint2rc file to `~/.config/tint2`, and set a keybind to run 'unam-osd' when pressed.
