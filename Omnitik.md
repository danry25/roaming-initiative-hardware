#Omnitik

An Omnitik is a radio with an integrated router and antenna made by MikroTik, it is weatherproof and preforms well. Omnitiks can be had for around $30 on eBay or in group buys. 

##Hardware

The base model Omnitik includes 5 10/100mbps ethernet ports, and a MiMo 2x2 802.11n radio. It can accept 8v to 30v of DC power injected into the ethernet cable via PoE on the Uplink port. The model above the base model offers PoE Out on ports 2 thru 5, but due to firmware issues the Omnitik may randomly turn off PoE on those ports, hence why most mod the base model to add PoE into the Omnitik. The Omnitik also has a 400mhz MIPS based SoC and 32mb of ram, along with 64mb of flash.

##Software

Omnitiks come with RouterOS v6, which is a custom made firmware based on the Linux kernel and mix of other utilities. OpenWRT and DD-WRT are not supported on the Omnitik yet, although it should be possible to support this platform.

##Modifications

###POE out

With this modification you can add Power Over Ethernet (POE) out on all 4 ethernet ports that are available for other devices to plug into on your Omnitik. Check out a [completed POE out mod](/Contrib/Tomás Aparicio/) & try it yourself.

###Antenna Alterations

There are many things you can do to the internal antennas in an Omnitik, from connectorizing them to  just making the existing ones a bit more directional using some tin foil and thin plastic sheathing. You can also use a dish to make an Omnitik directional, things like old satellite dishes, woks and even metal strainers or colanders will work to make your Omnitik into something that can go a few miles in a single direction.

##Relevant Links

[Manufacturer Page](http://routerboard.com/RBOmniTikU-5HnD)
