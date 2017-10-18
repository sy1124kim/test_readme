# test_readme

# Overview
dockzen-os make the boot image and platform image for docker. 

# Build 
<ul> 1. Save boot image and platform image to "/images" folder.
  <ul> - boot image : <br>
    - platform image : </ul>
  2. Edit file of "setting.sh".
  
  3. build image
  <ul> - rpi3</ul>
  
     $ ./build.sh  
     $ ./build.sh rpi3  
  <ul> - iiot</ul>
  
     $ ./build.sh iiot
  <ul> - resize </ul>
  
     $ ./build.sh resize
</ul>

# Fusing
Save platform image and boot image to SD card.
<ul>
  - rpi3
  
     $ ./sd_fusing.sh 
     $ ./sd_fusing.sh rpi3
  
  - iiot
  
     $ ./sd_fusing.sh iiot
  
  - resize
  
     $ ./sd_fusing.sh resize
</ul>
