RCOMP 2021-2022 Project - Sprint 2 - Member 1201525 folder
===========================================

### VLAN ID's
VLAN 311 - B3_EU_F0
<br>
VLAN 312 - B3_EU_F1
<br>
VLAN 313 - B3_WIFI
<br>
VLAN 314 - B3_DMZ
<br>
VLAN 315 - B3_VOIP
<br>
### Building 3 nodes required and adress blocks

|  Network  |Required Nodes|   Address Blocks   |
|-----------|--------------|--------------------|
|GroundFloor|      35      |64 adress block-/26 |
|FirstFloor |      45      |64 adress block-/26 | 
|WI-FI      |      55      |64 adress block-/26 |
|DMZ        |      28      |32 adress block-/27 |
|VoIP       |      25      |32 adress block-/27 |
|Total      |      188     |                    |

<br>

|      Name    |     IP Address      |
|--------------|---------------------|
|Initial IP    |172.17.69.0/24       |
|WI-FI         |172.17.69.0/26       |
|FirstFloor    |172.17.69.64/26 (0+64)   |
|GroundFloor   |172.17.69.128/26 (64+64) |
|DMZ           |172.17.69.192/27 (128+64)|
|VoIP          |172.17.69.224/27 (192+32)|
|Final IP      |172.17.69.256(224+32)|