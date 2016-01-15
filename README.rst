Styler README
=============

This repository is a fork of the 3.x branch of https:////github.com/opengeo/suite
just for the styler we still use, and do improvements on it.

#. Clone the repository::

     % git clone git://github.com/landryb/styler.git suite
     % cd suite/styler

#. Install jsbuild from JSTools::

     % easy_install jstools

#. Initialize submodule dependencies::

     % git submodule update --init --recursive

#. Do a full build::

     % jsbuild build.cfg -o script

#. Deploy the styler::

     % scp -r index.html theme script host:/path/to/geoserver/datadir/www/styler/

#. Test on http://url.to.geoserver/www/styler/
