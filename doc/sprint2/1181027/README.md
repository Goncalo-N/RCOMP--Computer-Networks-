RCOMP 2021-2022 Project - Sprint 2 - Member 1180127 folder
===========================================


#### Building 1 ####
### VLAN ID's ###
* VLAN 300 - Campus
* VLAN 301 - B1_EU_F0
* VLAN 302 - B1_EU_F1
* VLAN 303 - B1_WIFI
* VLAN 304 - B1_DMZ
* VLAN 305 - B1_VOIP

### IPv4 Addresses Blocks ### 
* **End Users Floor 0** - 60 nodes - 64 address block - /26
* **End Users Floor 1** - 80 nodes - 128 address block - /25
* **Wi-Fi** - 120 nodes - 128 address block - /25
* **DMZ** - 100 nodes - 128 address block - /25
* **VoIP** - 40 nodes - 64 address block - /26


* **Backbone** - 120 nodes - 128 address block - /25

---

* **Initial IP** - 172.17.64.0/22


* **Backbone** - 172.17.64.0/25
* **Wi-Fi** - 172.17.64.128/25 (0+128)
* **DMZ** - 172.17.65.0/25 (128+128)
* **End Users Floor 0** - 172.17.65.128/25 (0+128)
* **End Users Floor 1** - 172.17.66.0/26 (128+128)
* **VoIP** - 172.17.66.64/26 (0+64)


* **Final IP** - 172.17.66.128 (64+64)