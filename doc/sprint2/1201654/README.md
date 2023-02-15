RCOMP 2021-2022 Project - Sprint 2 - Member 1201654 folder
===========================================


#### Building 2 ####
### VLAN ID's ###

* VLAN 306 - B2_EU_F0
* VLAN 307 - B2_EU_F1
* VLAN 308 - B2_WIFI
* VLAN 309 - B2_DMZ
* VLAN 310 - B2_VOIP

### IPv4 Addresses Blocks ### 
* **End Users Floor 0** - 25 nodes - 32 address block - /27
* **End Users Floor 1** - 50 nodes - 64 address block - /26
* **Wi-Fi** - 120 nodes - 128 address block - /25
* **DMZ** - 12 nodes - 16 address block - /28
* **VoIP** - 12 nodes - 16 address block - /28

---

* **Initial IP** - 172.17.68.0/24

* **Wi-Fi** - 172.17.68.0/25 
* **End Users Floor 1** - 172.17.68.128/26 (0+128)
* **End Users Floor 0** - 172.17.68.192/27 (128+64)
* **DMZ** - 172.17.68.224/28 (192+32)
* **VoIP** - 172.17.68.240/28 (192+16)

* **Final IP** - 172.17.68.256 (240+16)