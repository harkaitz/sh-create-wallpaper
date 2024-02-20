# SH-CREATE-WALLPAPER

Create and install wallpapers on the different machines you manage.

## Help

create-wallpaper

    Usage: create-wallpaper -V | [-i FACEIMG][-t HOSTNAME] OFILE
    
    Create a custom wallpaper for a machine using ImageMagick(1). The
    wallpaper is gray with the HOSTNAME at top right and an optional
    image (logo) below.

ssh-h-wallpaper

    Usage: ssh-h-wallpaper SSH,...
    
    Create custom wallpapers with create-wallpaper(1) for the machines
    and upload to the computers.
    
    (i)  Only works for MS Windows using Busybox shell.
    (ii) Requires https://github.com/harkaitz/sh-ssh-helpers.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
