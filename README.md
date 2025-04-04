SSH DESKTOP
===========

Access remote desktops using SSH.

## Help

ssh-h-desktop

    Usage: ssh-h-desktop { -V | [-r (raw)] SSH }
    
    Open a desktop in a remote machine using TigerVNC.
    
    Env: DESKTOP_VNCPASS
    Config: ~/.dsetup.cfg, /etc/X11/dsetup.cfg

xinit-su

    Usage: xinit-su { -V | COMMAND... }
    
    Launch Xorg as root and then using sudo/doas change to user, set
    the wallpaper and configure screens with xrandr.
    
    Environment variables: SUDO_{R,U},DESKTOP_{XSETROOT,XRANDR}
    Config files: ~/.dsetup.cfg, /etc/X11/dsetup.cfg
    Log files: ~/.desktop.log

## Collaborating

For making bug reports, feature requests, support or consulting visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
