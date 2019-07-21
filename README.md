# Enable_IPS_Capture in Check Point R80.X
Script to enable Packet Capture on all IPS protections in a provided profile

This script is run on the SmartCenter or MDS server where the SmartCenter/Domain exists

**Please note that any protection that is changed will convert into a custom override!  This includes profile settings on each protection.**

**To run the script provide the Domain and profile to the script as shown below**
```
./set_capture My_Domain1 My_IPS_Profile
```

**For SmartCenter replace the Domain name with SMARTCENTER as shown below**
```
./set_capture SMARTCENTER My_IPS_Profile
```

Tested on R80.30GA SmartCenter and MDS
