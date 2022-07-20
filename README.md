# Lacp


Script Bonding LACP

First of all, you’ll have to find which interface have to be bond.
You can compare the result as the one observe during the “ip a” in the Workshop.
Then download the script

Tips : Script can be downloaded onto the server with a wget.
Wget link

You will then have to Rename it as “bond.sh” 
Tips : MV command can be used to do so, 
“mv lapc.sh bond.sh” 

Give the script the authorization to be loaded :
chmod +x bond.sh

Once it is done, you can use the script : 
./bond.sh  -i bond0 eth2 eth3

Argument used on the script : 
- i : Bond Name 
- d : If it does DHCP or not.
last argument is to set up which interface has to be bond.
