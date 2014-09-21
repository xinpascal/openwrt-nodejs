OpenWrt package feed for nodejs
=====

[![Build Status](https://travis-ci.org/xinpascal/openwrt-nodejs.svg?branch=master)](https://travis-ci.org/xinpascal/openwrt-nodejs)

This is an OpenWrt package feed containing community maintained nodejs packages.

To use these packages, add the following line to the feeds.conf
in the OpenWrt buildroot:

	src-git nodejs git://github.com/xinpascal/openwrt-nodejs.git
  
Update the feed:

	./scripts/feeds update nodejs 
  
Activate the package:

	./scripts/feeds install -a -p nodejs
  
The nodejs packages should now appear in menuconfig.


