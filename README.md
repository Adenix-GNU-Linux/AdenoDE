# AdenoDE-1.0 Beta
The first version of the Adenosine Desktop Environment.
(Recommended Distros: Debian, Ubuntu)
Note: Live ISO addition is in beta testing.

# Dependencies
I3 Window Manager (i3),
Nitrogen,
Adwaita Icon Theme (adwaita-icon-theme),
Gnome Panel (gnome-panel),
Plank,
Xorg

# How to Install
1. Install the dependencies:
   (sudo apt install i3 nitrogen adwaita-icon-theme gnome-panel plank xorg --no-install-recommends)
3. Move adenoDE.sh to /bin/
  (mv [directory location]/adenoDE.sh /bin/)
5. Move adenoDE.desktop to /usr/share/xsessions
  (mv [directory location]/adenoDE.desktop /usr/share/xsessions)
# Usage
1. Logging in
  a. Log out of current desktop environment (if using for first time)
  b. Find "AdenoDE" and log in
2. Logging out
  a. Press mod+shift+e
  b. The i3 window manager will ask for confirmation before you log out. If you are logging out,    press the button that says "Yes, exit i3". You will then exit the desktop environment.
3. Opening & closing the terminal
   Press mod+enter to open a new terminal window. Press mod+shift+q to close it
4. Shutting down
   a. Terminal option
     Open the terminal and type in systemctl poweroff
   b. Standard option
     Log out of the desktop environment & shutdown the computer using the display manager.
