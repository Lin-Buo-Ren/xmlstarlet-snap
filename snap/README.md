# Unofficial Snap Packaging for XMLStarlet Command Line XML Toolkit
<!--
	Use the Staticaly service for easy access to in-repo pictures:
	https://www.staticaly.com/
-->
![Logo of XMLStarlet Command Line XML Toolkit](gui/xmlstarlet.adapted.png "Logo of XMLStarlet Command Line XML Toolkit")

**This is the unofficial snap for XMLStarlet Command Line XML Toolkit**, *"A set of command line utilities (tools) which can be used to transform, query, validate, and edit XML documents"*. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

[![Build Status Badge of the `xmlstarlet` Snap](https://build.snapcraft.io/badge/Lin-Buo-Ren/xmlstarlet-snap.svg "Build Status of the `xmlstarlet` snap")](https://build.snapcraft.io/user/Lin-Buo-Ren/xmlstarlet-snap)

![Screenshot of the Snapped Application](local/screenshots/xml%20--version.png "Screenshot of the Snapped Application")

Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters

## Installation
([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### In Terminal
    # Install the snap package #
    sudo snap install xmlstarlet
    
    # Connect the snap to optional security confinement interfaces #
    ## For accessing files under `/mnt` or `/media` ##
    sudo snap connect xmlstarlet:removable-media
    
    # Launch the application #
    xmlstarlet --help
    
    ## If you have another existing XMLStarlet installation ##
    snap run xmlstarlet --help
    
    xmlstarlet.xml --help
    
    ## After running `sudo snap alias xmlstarlet.xml xml` to create a command alias ##
    xml --help

### The Graphical Way
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/xmlstarlet)

## What is Working
* `xml validate _xml_file_`
* `xml format _xml_file_`

## What is NOT Working...yet 
Check out the [issue tracker](https://github.com/Lin-Buo-Ren/xmlstarlet-snap/issues) for known issues.

## Support
* Report issues regarding using this snap to the issue tracker:  
  <https://github.com/Lin-Buo-Ren/xmlstarlet-snap/issues>
* You may also post on the Snapcraft Forum, under the `snap` topic category:  
  <https://forum.snapcraft.io/c/snap>
