RCOMP 2021-2022 Project - Sprint 2 - Member 1200801 folder
===========================================


#### Building 5 ####
### VLAN ID's ###

* VLAN 321 - B5_EU_F0
* VLAN 322 - B5_EU_F1
* VLAN 323 - B5_WIFI
* VLAN 324 - B5_DMZ
* VLAN 325 - B5_VOIP

### IPv4 Addresses Blocks ### 
* **End Users Floor 0** - 40 nodes - 64 address block - /26
* **End Users Floor 1** - 55 nodes - 64 address block - /26
* **Wi-Fi** - 60 nodes - 64 address block - /26
* **DMZ** - 20 nodes - 32 address block - /27
* **VoIP** - 25 nodes - 32 address block - /27

---

* **Initial IP** - 172.17.71.0/24

* **Wi-Fi** - 172.17.71.0/26
* **End Users Floor 0** - 172.17.71.64/26 (0+64)
* **End Users Floor 1** - 172.17.71.128/26 (64+64)
* **DMZ** - 172.17.71.192/27 (128+64)
* **VoIP** - 172.17.71.224/27 (192+32)

* **Final IP** - 172.17.71.256 (224+32)