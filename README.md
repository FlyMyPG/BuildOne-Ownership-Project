# The BuildOne Ownership Project  

A curated guide to take a total beginner from zero to a working BuildOne 3D printer and a great First Print, then make it better!  

***Please read everything!***  Even if you are highly experienced, this will ensure you know what is being shared with our beginners.

***Please follow every link!***  This document is all about the links. Words will be deleted as more and better links are found. It is possible this entire document will become unnecessary when the [BuildOne Wiki](https://digistump.com/wiki/buildone) fully matures. (***Erik: Please copy freely from this page!***)

This guide tries to provide the minimum needed to ensure initial success, and some hints for what could come next.  Beyond that, it is up to each BuildOne owner to follow their own interestes and needs, which relies on three major factors:  
- Self-education: It is easy to become overwhelmed by the amount of knowledge and skill needed to become proficient in 3D Printing and 3D Design.  
  - This guide tries to reference only the highest-quality resources, each of which contains far more information than is linked here.  
  - Going beyond the links here is simplified by becoming proficient at using search engines.  
    - Learn the "[language](https://www.3dprinting-glossary.com/full/)" of 3D printing, so you can search for things using the same words others use.  
    - Learn search engine "[tricks](https://www.google.com/search?client=opera&q=search+engine+tricks&sourceid=opera&ie=UTF-8&oe=UTF-8)" to reduce junk in the results.  The most important of these are the [search results filters](https://support.google.com/websearch/answer/142143?hl=en), of which I find the `Tools → Any time → Past year` filter most useful to help me focus on the newest information.  
- Join the Community: There are countless online communities for 3D printing.  The following examples are good places to start, each of which will lead you to others:  
  - The [Robotic Industries Community Forum](https://www.robotic.industries/community).  Just for us.  Focused, yet limited.  
  - Reddit: The [r/3dprinting](https://www.reddit.com/r/3Dprinting/) subreddit is where folks talk about what they're doing today.  
  - [Thingiverse](https://www.thingiverse.com/) isn't just a place to freely download ready-to-print designs, but is also a place to talk with the creators about their designs.  
- Ask questions!  Be fearless.  Be patient yet persistent.  Let the community know you are a beginner, and let them begin by helping you focus your question.  I recommend starting your first questions with "Is this a good place to ask about \<*insert your topic*\>?".  Always behave kindly, and simply ignore those who don't do likewise (no flame wars).  

Ready?  Let's go!  

## Table of Contents

   * [The BuildOne Ownership Project](#the-buildone-ownership-project)
      * [What is "3D Printing"?](#what-is-3d-printing)
      * [How do I assemble and test my BuildOne kit?](#how-do-i-assemble-and-test-my-buildone-kit)
      * [How do I make my BuildOne better?](#how-do-i-make-my-buildone-better)
         * [Fix the Kit:](#fix-the-kit)
         * [Add Features:](#add-features)
         * [Maintenance:](#maintenance)
      * [How do I make my prints better?](#how-do-i-make-my-prints-better)
         * [Filament Selection:](#filament-selection)
         * [Filament Settings:](#filament-settings)
         * [Slicer Settings:](#slicer-settings)
   * [BuildOne Major Options and Add-Ons](#buildone-major-options-and-add-ons)
      * [Laser Engraver](#laser-engraver)
         * [Assembly](#assembly)
         * [The first Engraving Project](#the-first-engraving-project)
         * [An Intensity/Speed Calibration Test Print](#an-intensityspeed-calibration-test-print)
      * [Dual-Filament](#dual-filament)
         * [Overview](#overview)
         * [Assembly](#assembly-1)
         * [Dual-Filament Test Print](#dual-filament-test-print)
      * [3D Scanner](#3d-scanner)
         * [Assembly](#assembly-2)
         * [The first 3D scan](#the-first-3d-scan)

 > _Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc)_

## What is "3D Printing"?  
  - ***Please*** watch Thomas Sanladerer's "[3D Printing Basics](https://www.youtube.com/watch?v=nb-Bzf4nQdE&list=PLDJMid0lOOYnkcFhz6rfQ6Uj8x7meNJJx)" playlist on YouTube.  Seriously. This answers so many questions before you'll know they needed asking. Little from those videos is copied here, so that's the place to go for that content.  
    
  - [3D Printing has it's own language](https://www.3dprinting-glossary.com/full/). You won't be understood if you don't speak it. There's no need to learn what ***all*** the words mean, but do skim through it to know what words are used, then return later when you need the definition.  
  
  - BuildOne Design: Most hobby/home 3D printers have a "[RepRap](https://reprap.org/wiki/RepRap)" design, where the bed moves horizontally.  The BuildOne has a "[CoreXY](https://all3dp.com/2/corexy-3d-printer-is-it-worth-buying/)" design that moves the bed vertically.  Another popular and distinctly different design is the "[delta](https://all3dp.com/2/what-is-a-delta-3d-printer-simply-explained/)" with a stationary bed, and there are yet [more designs](https://all3dp.com/know-your-fdm-3d-printers-cartesian-delta-polar-and-scara/) possible.  

## How do I assemble and test my BuildOne kit?  
  - Getting Ready:  
    - [Prepare your build space](https://www.robotic.industries/community/d/36-buildone-is-it-pre-assembled/7).  
    - Gather tools and consumables:  
      - ESD Gloves [like these](https://smile.amazon.com/Global-Glove-Polyurethane-Coated-Gloves/dp/B00GWRDHIM).  Electronics can be delicate, acrylic can be sharp, and skin is easily pinched!  I use these at home and work.  
      - Hex keys. (sizes? lengths?)  I prefer ball-end ones [like these](https://www.harborfreight.com/13-piece-metric-ball-end-hex-key-set-96416.html).  
      - Nut wrenches/sockets. (sizes?)  When in doubt, a tiny 4" adjustable wrench [like this](https://smile.amazon.com/Fityle-Adjustable-Spanner-Wrench-Opening/dp/B07N2CPJPY) is useful.  
      - Screwdrivers. (flat, Phillips, others?)  
      - Combination Square [like this](https://smile.amazon.com/Johnson-Level-Tool-400EM-S-Combination/dp/B00002N5O9).  
      - Alcohol cleaning pads [like these](https://smile.amazon.com/Dynarex-Alcohol-Prep-Sterile-Medium/dp/B005BFL0RQ).  
      - Bearing and rod lubricant [like this](https://smile.amazon.com/Super-Lube-Purpose-Synthetic-Dielectric/dp/B00KU85W4G).  

  - Assembly Instructions:  
    - [Clean and lubricate](https://prusacommunity.com/set-your-bearing-straight/) every bearing and shaft before assembly!  Manufacturers coat bearings to make them last in storage, not function in use.  Do this now to avoid having to take apart your BuildOne to do it later.  
    - [Manufacturer's Instructions](https://digistump.com/wiki/buildone/basekit).  
    - [BobC's Comments on them](https://www.robotic.industries/community/d/110-wiki-assembly-instructions-some-comments-on-what-s-been-posted-so-far/9).  Most importantly, it contains a link to the ***correct*** way to assemble an E3D v6 hot-end.  
    
  - Installation of Basic Optional Components:  
    - Axis Upgrade  
    - Heated Bed  
    - Display  
    - [Enclosure](https://digistump.com/wiki/buildone/enclosurekit)  

  - Setup:  
    - Check printer is square on each axis.  
    - Manual bed leveling.  
    - Format USB drive / microSD card.  
    - Slicer configuration:  
      - Cura  
        - [Manufacturer's Configuration](https://digistump.com/wiki/buildone/cura)  
        - Community contributions  
      - Simplify3D  

  - First Print:  
    - Ready-to-Print GCODE  
     - Files Erik provides...?  

  - Second Print:  
    - Basic Slicing  
     - Benchy the Boat  
       - You ***must*** print a Benchy. Nobody will acknowledge your existence until you do. It's a "Rite of Passage" for beginners.  
       - Its by far the easiest way to get help with your printer and slicer, since ***everyone*** has printed a Benchy.
       - Benchy has a [True Home](http://www.3dbenchy.com/). Please get your authentic Benchy STL file through their links.  

## How do I make my BuildOne better?  
  
### Fix the Kit:  
  - Strengthen the Platform  
  - Add a Removable Build Surface  
  - Update the Firmware  
    
### Add Features:  
  - [BuildOne Forum for Mods](https://www.robotic.industries/community/t/buildone-mods).  
    
### Maintenance:  
  - Continuous Maintenance:  
    - Keep your filament dry.  
    - Keep your print bed clean.  
    - Keep your nozzle clean (cold-pull).  
  - Minor Maintenance and Inspection:  
    - Special cleaning filament,  
    - Complete wipe-down / dusting.  
    - Inspection:  
      - Nozzle  
      - Z-axis Acme (worm) screw and nut  
      - All smooth rods  
      - The belt  
      - Pulleys  
      - All acrylic parts  
      - Screws, bolts and nuts  
  - Major Maintenance:  
    - [Overview video by Maker's Muse](https://www.youtube.com/watch?v=v8SwY8yveqc).  
      
## How do I make my prints better?
  
### Filament Selection:
  - Use only PLA at first  
  - Generic Filament:  
    - There is very little "bad" filament on the market any more, so even inexpensive brands from reputable retailers should give excellent results.  
    - That said, beware of "too good to be true" prices on markets like eBay or AliExpress.  
    - [Amazon](https://smile.amazon.com):  
      - "Amazon's Choice" means nothing special. It is just advertising, a tag sellers can purchace.  
      - "Amazon Brand" and "AmazonBasics" mean it was made just for Amazon, and generally represents good quality and value.  
  - Recommended Brands:  
    - Bang-for-the-Buck:  Solutech, eSun, Ziro  
    - Masters of Filament:  Hatchboxx, Prusament, Proto-pasta, Polymaker, Colorfabb, Ninjaflex (Flexible, TPE/TPU)
    
### Filament Settings:  
  - The Basics:  
    - Start with whatever temperatures the manufacturer recommends, with the default slicer speeds.  Only go further when the cause of a bad print has been specifically traced to filament (rather than slicer) issues.   
  - Pursuing Perfection:  
    - Print various [Calibration Towers](https://www.thingiverse.com/search?q=calibration+tower&type=things&sort=text&page=1) to identify and fix/optimize many common problems, including speed, nozzle temperature and part cooling:  

### Slicer Settings:  
  - Speed / Quality:  
    - Line Width  
    - Layer Thickness  
    - Infill  
    - Wall Thickness  

# BuildOne Major Options and Add-Ons  

## Laser Engraver  

### Assembly  
  - Erik's instructions on wiki...  
  - Corrections to Erik's instructions...  
  
### The first Engraving Project  
  - A Diagram of the BuildOne on Birch plywood  

### An Intensity/Speed Calibration Test Print  
  - What is the equivalent of a Benchy for engraving?  
  - [Use Inkscape to create an SVG drawing and convert it to gcode](https://www.ctoom.com/tutorial/how-to-create-g-code-file-with-inkscape/).  
  
## Dual-Filament  

### Overview  
There are multiple ways to use multiple filaments in a single print.  [Here's a great overview](https://www.fabbaloo.com/blog/2018/3/16/the-several-methods-of-dual-extrusion).  

The BuildOne dual-filament option is a "filament switcher", not a "dual hot-end" system. Like most other dual-filament systems it has a second filament feed system, but comes with some advantages and disadvantages:  
Advantages:  
  - No second hot-end.  
  - No special firmware.  
  - Fast and Easy to add.  
Disadvantages:  
  - Slow for each color change.  Steps include:  
    - Full filament retraction  
    - Full and full feed  
    - Purge of prior color from nozzle  
  - Filament purge wastes filament, often more than is used by the print itself!  
  
  _**Mod Hint:** If you also purchased the BuildOne Spare Parts Add-On, it includes a second hot-end that can be used to create a true dual hot-end mod for the BuildOne._  

### Assembly
  - [Manufacturer's Instructions](https://digistump.com/wiki/buildone/laserkit)  
  - Corrections to Erik's instructions...  
  
### Dual-Filament Test Print 
  - ???

## 3D Scanner  

### Assembly  
  - [Manufacturer's Instructions](https://digistump.com/wiki/buildone/scannerkit)  
  - Corrections to Erik's instructions...  
  
### The first 3D scan  
  - One of the test prints? (Easy to verify.)  

