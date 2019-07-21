# Enable_IPS_Capture
Script to enable Packet Capture on all IPS protections

This script is run on the MDS server where they CMA/Domain exists

Change the CMA/Domain and Profile variable at the top of the script for the desired profile/domain

**Please note that any protection that is changed will convert into a custom override!  This includes profile settings on each protection.**

**To run the script provide the Domain and profile to the script as shown below**
```
./set_capture My_Domain1 My_IPS_Profile
```

**For SmartCenter replace the Domain name with SMARTCENTER as shown below**
```
./set_capture SMARTCENTER My_IPS_Profile
```
