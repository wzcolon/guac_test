Guacomole Test
==============

This repo has been set up to test the guacomole scripts

Server Configuration
--------------------

1. install nginx
2. install guacomole server

   add `deb http://mirrors.kernel.org/ubuntu trusty main` to /etc/apt/sources.list

   `sudo apt-get install -y libcairo2-dev libjpeg62-dev libpng12-dev libossp-uuid-dev`

   For RDP support, install `libfreerdp-dev`

   For OpenSSL support, install `libssl-dev`

   For VNC support, install `libvncserver-dev`
3. clone the Guacamole project
   `git clone git://github.com/glyptodon/guacamole-server.git`
