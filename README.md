SSH DESKTOP
===========

Access remote desktops using SSH.

## Help

ssh-h-tigervnc

    Usage: ssh-h-tigervnc [-s][-W][-w PASS][-d DISPLAY] USER@HOST
    
    Connect to a machine using ssh(1) and tunnel a VNC session.
    
      -V          Show configuration.
      -M          Multimonitor.
    
      -s          Launch vncserver in the remote host.
      -W          Set random password in the remote host.
      -w PASS     Get password with "pass PASS".
      -d DISPLAY  Redirect this display, default (1)
      -b ADDRESS  The remote address with VNC server (127.0.0.1)
      -c          Check connection and quit.
      -k          Shutdown server and quit.
      -X PROGRAM  Launch this program.
      -K PATTERN  Kill this programs when launching a server to log out
                  any user.
    
    Environment variables: SSH PASS VNC_MONITOR

## Collaborating

Feel free to open bug reports and feature/pull requests.

More software like this here:

1. [https://harkadev.com/prj/](https://harkadev.com/prj/)
2. [https://devreal.org](https://devreal.org)
