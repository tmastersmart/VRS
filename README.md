# VRS
Aviation chart overlays for Virtual Radar Server. 

Working on Visual Radar Server under Mono on PI
Version:2.4.4.36598 Environment: Mono 64-bit


Forked from. https://github.com/ProHill/VRS-Charts


##Prerequisites
- VRS installed and running
- VRS Custom Content Plugin installed
- VRS Maps set to google maps

##Instructions

- Clone or download the repo into a directory outside the VRS directory /home/pi/VRS-Custom/
- Configure the VRS Custom Content Plugin as shown below

Enabled	Inject	At	Of	Address	

/home/pi/VRS-Custom/headeradd.html	    End Head /desktop.html	 
/home/pi/VRS-Custom/map_toolbar.html	    End Body /desktop.html	 
/home/pi/VRS-Custom/custom-map.html  	    End Body /desktop.html	 
/home/pi/VRS-Custom/map_toolbar-mobile.html End Head /mobile.html

