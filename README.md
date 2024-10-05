# SH-CREATE-WALLPAPER

Create and install wallpapers on the different machines you manage.

## Help

create-wallpaper

    Usage: create-wallpaper -V | [-i FACEIMG][-t HOSTNAME] OFILE
    
    Create a custom wallpaper for a machine using ImageMagick(1). The
    wallpaper is gray with the HOSTNAME at top right and an optional
    image (logo) below.

ssh-h-starticon

    Usage: ssh-h-starticon { -V | SSH,... }
    
    Copy a start icon ~/.start.png to remote machines.
    
    Environment variables: SSH_H_STARTICON

ssh-h-wallpaper

    Usage: ssh-h-wallpaper SSH,...
    
    Create custom wallpapers with create-wallpaper(1) for the machines
    and upload to the computers.
    
    It will use $SSH_H_WALLPAPER_DIRECTORY/SSH.jpg face image if it
    exists when creating the wallpaper.
    
    In windows machines the wallpaper will be set using reg and USER32.DLL.
    In other machines you will need to set "~/.wallpaper.png" manually.
    
    (i)  Only works for MS Windows using Busybox shell.
    (ii) Uses ssh-h-list if found https://github.com/harkaitz/sh-ssh-helpers.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
