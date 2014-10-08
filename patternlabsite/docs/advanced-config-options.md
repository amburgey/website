---
layout: docs
title: Editing the config.ini Options | Pattern Lab
---

Pattern Lab comes with a simple configuration file that allows you to modify certain aspects of the system. The following example configuration is from `v0.7.9` of Pattern Lab.

    /*
     * Configuration Options for Pattern Lab
     * If config.ini doesn't exist Pattern Lab will try to create a new version
     */

    v  = "0.7.9"

    // file extensions to ignore when building or watching the source dir, separate with a comma
    ie = "scss,DS_Store,less"
    
    // directories and files to ignore when building or watching the source dir, separate with a comma
    id = "scss,.svn,.sass-cache"
    
    // choose if these services should be loaded in the nav and their ports
    autoReloadNav  = "true"
    autoReloadPort = "8002"
    pageFollowNav  = "true"
    pageFollowPort = "8003"
    
    // whether the qr code generator should be loaded automatically in the nav
    qrCodeGeneratorOn = "false"
    
    // pattern lab's xip host if you have it configured, to be used with the QR code generator
    xipHostname = "http://patternlab.*.xip.io"
    
    // whether the public directory should be cleaned when generating your site
    cleanPublic = "true"
    
    // the minimum and maximum for the viewport resizer
    ishMinimum = "240"
    ishMaximum = "2600"
    
    // which, if any, controls to hide in the nav, separate with a comma
    ishControlsHide = "hay"
    
    // the order of pattern states, css class names
    patternStates = "inprogress,inreview,complete"
    
    // the pattern types that shouldn't be included in the style guide, useful if you nest pages/templates
    styleGuideExcludes = ""
    
    // should the cache buster be on, set to false to set the cacheBuster value to 0
    cacheBusterOn = "true"