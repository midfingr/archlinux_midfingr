
Changes to Arch Linux Midfingr Edition builds

Build naming changed. Now reflects month-day-year.

archmidfingr-2015.06.10-x86_64.iso

log in password: guest
log in root password: root  ### !! CHANGE ASAP !! ###

Changes to 06-10-15

- support for btrfs (a.k.a. better file system, etc.)
- fstab changed to UUID
- Firefox web browser
- modified reflector instructions in Post Install
- Thunar bookmark to applications (renamed to Programs)
- Linux kernel 4.x
- Whisker menu 'Numix' based theme


## !! Attention !! ## Nvidia 900 series card users
Before booting the Arch ISO:
- press tab
- press space at the end
- type: nomodeset
- press ENTER
This should allow Nvidia 900 series card users to continue to the GUI; not need if running from Virtualbox or similar

Changes to 04-28-15

- based on Nvidia xorg (nvidia-libgl) ## may not work for AMD/ATI graphics cards
- traditional root access
- additional documentation 'Post Install Addendum', 'What's New', 'Important' (change root pass), 'Keyboard Layout'
- Icon Theme: Numix Circle
- workaround for Virtualbox (host) 'VERR_SUPLIB_OWNER_NOT_ROOT' error
- NetSurf as Web Browser; reduces ISO size, remove and or replace as needed
- keyboard layout plugin on bottom panel; manually add if desired
- makepkg config modified for multicore compression and memory based compilation
- '.scripts' folder; free memory, Thunar scripts and logout
- leafpad font set to Cantarell Bold; user and root
Thunar:
- add copy and move to actions have been REMOVED

!! Attention !! Nvidia 900 series card users
Before booting the Arch ISO:
- press tab
- press space at the end
- type: nomodeset
- press ENTER
This should allow Nvidia 900 series card users to continue to the GUI; not need if running from Virtualbox or similar

archmid-03-10-15_x86_64.iso

log in password: guest

Changes to 03-10-15

- xfce 4.12 Final !!
- mkinitcpio is back to default
- grub2 theme 'arch-suse'
- additional documentation 'Post Install Addendum' & 'What's New'

complied on March 09 2015

archmid-03-05-15_x86_64.iso

log in password: guest

Changes to 03-04-15

- xfce 4.12 testing repository
- edited mkinitcpio file to aid in boot time
please see: http://blog.falconindy.com/articles/optmizing-bootup-with-mkinitcpio.html
- Whisker menu added back with transparency (xfce4-whiskermenu-plugin)
- panel background color set to black; 80% alpha

Note this is from the Arch Linux Testing Repository. To view bugs, please see:
https://bbs.archlinux.org/viewtopic.php?id=194313


archmid-02-19-15_x86_64.iso

log in password: guest

Changes to 02-19-15

Thunar:
- add copy and move to actions;  right-click mouse
- F3 to open new TAB
- F4 to open terminal

---------------------------------------------------------------------

- '.scripts' folder; free memory, Thunar scripts and logout
- leafpad font set to Cantarell Bold; user and root
- icon theme: Ultra Flat
- window/login manager is now LXDM
- bottom panel includes shortcut to XFCE System Settings
- removed whisker in favour of default menu
- Chromium replaces Firefox
- added ctrl+alt+backspace keyboard shortcut to log out

archmid-01-10-15_x86_64.iso

log in password: guest

Changes to 01-10-15

- fixed file system permissions warning
- Firefox customizations
- post-clean now includes option to clear pacman cache
- pacman configuration file includes colors and 'I-Candy' ;)

archlinux_midfingr_x86_64-0.12

Video: http://youtu.be/fvjC9M-Vrfg

log in password: guest

Changes to v0.12

- compatibilty with recent XFCE4 updates
- speedtest-cli added ; alias speed
- changed journal configuration to use 50 MB maximun
- updated documentation
- numix theme
- transparent panel

archlinux_midfingr_x86_64-0.10

log in password: guest

Changes to v0.10

- new installer (ame) and instructions
- xfce4 drop-down terminal
- speedtest-cli (type speed in a terminal)
- localepurge (needs configuration)
- multi-user environment
- updated instructions to change the default user
- firefox theme delorean-dark
- removed guake terminal

archlinux_midfingr_x86_64-0.09b

log in password: guest

Changes to v0.09b

- removed update manager # too many problems
- added Chromium (chromium-pepper-flash-standalone) # as per request
- removed unneeded themes, fonts and icons
- updated the Post Install document
- added compiz-brz
- a couple of conky-colors tweaks
- removed mate terminal
- added 'Edit as Root' for documents
- updated to xorg-server 1.16 # Catalyst users will need to downgrade this to 1.15

archlinux_midfingr_x86_64-0.09

Changes to v0.09

- added additional configuration notes on desktop
- added guake terminal (press F12)
- removed compiz start/stop buttons: replace with keyboard shortcuts
- added a more compatible delorean-dark theme; should remove the gtk errors
- fireworks ! ;)
- GIMP added as per request
- back to one panel at the bottom
- more conky edits
- disabled compiz wallpapers & fixed a few issues
- window buttons are on center of panel

archlinux_midfingr_x86_64-0.08

Changes to v0.08

- password: guest
- new document 'before you begin' ; includes troubleshooting notes
- lightdm login manager ; customized
- main panel place at the top with some 'tweaks'
- additional panel at bottom ; hidden
- global dark theme; 'Delorean-Dark'
- XFCE windows open in center of the screen
- additional compiz tweaks including wallpaper cycling
- added extra Xorg packages

archlinux_midfingr_x86_64-0.07a

Changes to v0.07a

- included all default packages in the 'build.sh' script
- desktop icons are more transparent
- depmod to fix virtualbox bug
- changed 'how to' desktop icon
- removed window button labels

archlinux_midfingr_x86_64-0.07

Changes to v0.07

- all custom scripts are now global (no need to edit)
- customized an emerald theme by Billy Cantrell | bvc@gnomethemes.org (Rezlooks-PastelGreen)
- added a build version to conky script
- whisker menu theme using Graeme Gott's blog post (http://gottcode.org/xfce4-whiskermenu-plugin/)
- tweaked compiz settings; effects, colors, etc.
- window buttons in panel now show labels
- 'how to' desktop link no longer locked

archlinux_midfingr_x86_64-0.06a

Changes to v0.06a

- conky keyboard shortcuts added
- shade button in windows manager hidden
- cleaned up xfce4 desktop xml file
- 'How To Install' link added to desktop (youtube video)
- time zone set to UTC

archlinux_midfingr_x86_64-0.06

Release Notes

How To Install: https://www.youtube.com/watch?v=HotgBN4mpHs

archlinux_midfingr_x86_64-0.06

- removed script for motd
- added pulseaudo for soundcard compatibility
- fixed synapse to start on login
- xfce4 window manager settings now work as expected; i.e wallpaper size, fonts, panel icons, etc.
- removed Slim login manager
- added whisker menu with arch logo
- auto startx after username and password
- added grub boot theme
- removed redundant/unneeded packages; with the exception of xfce4-terminal
- added theme configuration (gtk-theme-config) for panel colors, etc.
- logout now logs out completely
- added conky-colors back in
- wallpaper and dual monitors seem to work properly
- secure erase with hdparm on SSD working

archlinux_midfingr_x86_64-0.05

- removed script for motd
- added pulseaudo for soundcard compatibility
- fixed synapse to start on login
- removed conky-colors
- xfce4 window manager settings now work as expected; i.e wallpaper size, fonts, panel icons, etc.
- removed Slim login manager
- added whisker menu with arch logo
- auto startx after username and password
- added grub boot theme
- removed redundant/unneeded packages; with the exception of xfce4-terminal
- added theme configuration (gtk-theme-config) for panel colors, etc.
- logout now logs out completely
