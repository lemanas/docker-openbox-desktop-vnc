# Openbox virtual desktop running in Docker container
Use VNC Viewer to access the desktop with ``root`` as the default password.

To change VNC password run ``vncpasswd``

Configurable variables
* ``GEOMETRY`` Specify the size of the desktop to be created. Default is ``1024x768``
* ``DEPTH`` Specify the pixel depth in bits of the desktop to be created. Default is ``16``
* ``TZ`` Specify timezone. Default: ``Etc/UTC``

![Screenshot](http://static.alekna.org.s3.amazonaws.com/github/docker-openbox-desktop-vnc-screenshot.jpg "Screenshot")