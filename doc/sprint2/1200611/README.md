RCOMP 2021-2022 Project - Sprint 2 - Member 1200611 folder
===========================================


#### Building 4 ####
# VLAN ID's 

  * VLAN 316  B4_EU_F0
  * VLAN 317  B4_EU_F1
  * VLAN 318  B4_WIFI
  * VLAN 319  B4_DMZ
  * VLAN 320  B4_VOIP


# Building 3 nodes required and adress blocks

**Network** | **Required Nodes** | **Adress Blocks**
------------|--------------------|-----------------
Wi-fi       | 70  | 128 address block /25
First Floor | 55  | 64  address block /26
Ground Floor| 28  | 32 address block /27
DMZ         | 10  | 16 address block /28
VoiP        | 12  | 16 address block /28
Total       | 175 | 

|**Name** | **IP Address**|
|---------|----------------|
|Inicial IP |172.17.70.0/24 |
|Wi-fi | 172.17.70.0/25 |
|First Floor | 172.17.70.128/26 (0+128) |
|Ground Floor | 172.17.70.192/27 (128+64) |
|DMZ | 172.17.70.224/28 (192+32) |
|VoiP | 172.17.70.240/28 (224+16) |
|Final IP | 172.17.70.256 (240+16) |