# VRS
Aviation chart overlays for Virtual Radar Server. For a live example, see http://flights.hillhome.org and http://flights.hillhome.org/VirtualRadar.

Working on Visual Radar Server under Mono on PI

Forked from. https://github.com/ProHill/VRS-Charts


##Prerequisites
- VRS installed and running
- VRS Custom Content Plugin installed

##Instructions

- Clone or download the repo into a directory on the machine where VRS is running. Ensure you do not place the files under the Virtual Radar Server directory, since they could be overwritten on upgrades.
- Configure the VRS Custom Content Plugin as shown below

Enabled	Inject	At	Of	Address	
	/home/pi/VRS-Custom/headeradd.html	        End	Head	/desktop.html	 
	/home/pi/VRS-Custom/map_toolbar.html	    End	Body	/desktop.html	 
	/home/pi/VRS-Custom/custom-map.html  	    End	Body	/desktop.html	 
	/home/pi/VRS-Custom/map_toolbar-mobile.html	End	Head	/mobile.html


Maps must be set to google maps in setup.
