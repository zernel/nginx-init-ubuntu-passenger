# nginx-init-ubuntu-rails #

Nginx init script for passenger default build on ubuntu.

Original Author: [Jason Giedymin](http://jasongiedymin.com) <jasong -_at_- apache -=dot=- org>

Check out my other [repos](http://github.com/JasonGiedymin)!

## Install ##

    cd /etc/init.d
    sudo wget https://raw.github.com/chloerei/nginx-init-ubuntu-passenger/master/nginx
    sudo update-rc.d nginx defaults
    sudo chmod +x nginx
    sudo service nginx start

## Notes ##
It is recommended to install [Nginx](http://nginx.net/) by doing a full compile & build. Not all package repositories keep their branches updated. For security it is your duty to maintain a good working environment and thus includes all interfacing applications.

A great resource is the [Nginx Wiki](http://wiki.nginx.org/).

## Contributions ##
_Contributions are welcome!_
