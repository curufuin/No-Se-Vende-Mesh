# No-Se-Vende-Mesh
OpenWRT configuration files for the No Se Vende mesh network in Los Angeles

On non-gateway nodes make sure you install the following packages with opkg:

batctl-full 
kmod-batman-adv 
luci-proto-batman-adv 
wpad-mesh-wolfssl

On gateway nodes make sure you install the following packages with opkg:

batctl-full 
kmod-batman-adv  
wpad-mesh-wolfssl


The default passwords for both the MeshCloud backhaul and the No Se Vende access point are "password," obviously this is not what will be used in production, this is for testing and development purposes only.  There is no root password by default, which is something you will want to change during the innitial setup of openWRT

The gateway is using the OpenWrt 19.07.9 firmware on WD N750 due to instability in the most recent firmware version.

The node is using the OpenWrt 23.05.0 firmware on WD N750, but will probably be rolled back to 19.07.9 in the future as well.

I will be compiling more in depth install notes in the future.
