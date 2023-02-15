RCOMP 2021-2022 Project - Sprint 2 planning
===========================================
### Sprint master: 1201654 ###

# 1. Sprint's backlog #

Task  |  Task description
------|---------------------------------------------------------------------------------------------------------
T.2.1 | Development of a layer two and layer three Packet Tracer simulation for building one, encompassing the campus backbone. Integration of every member’s Packet Tracer simulation into a single simulation.
T.2.2 | Development of a layer two and layer three Packet Tracer simulation for building two, encompassing the campus backbone.
T.2.3 | Development of a layer two and layer three Packet Tracer simulation for building three, encompassing the campus backbone.
T.2.4 | Development of a layer two and layer three Packet Tracer simulation for building four, encompassing the campus backbone.
T.2.5 | Development of a layer two and layer three Packet Tracer simulation for building five, encompassing the campus backbone.

# 2. Technical decisions and coordination #

  * Packet tracer version used: 8.0.0.0212.
  * VLANID domain name used: 300 - 330.
  * VTP domain name used: rc22dgg3.
  * IPv4 address used: 172.17.64.0/21.
  * ISP router IPv4 node address used: 15.203.47.141/30.
  
# 3. Subtasks assignment #

  * 1181027 - T.2.1
  * 1201654 - T.2.2
  * 1201525 - T.2.3
  * 1200611 - T.2.4
  * 1200081 - T.2.5

### VLANIDS and Respective Names
  * vlan 300 name Campus

  * vlan 301 name B1_EU_F0
  * vlan 302 name B1_EU_F1
  * vlan 303 name B1_WIFI
  * vlan 304 name B1_DMZ
  * vlan 305 name B1_VOIP

  * vlan 306 name B2_EU_F0
  * vlan 307 name B2_EU_F1
  * vlan 308 name B2_WIFI
  * vlan 309 name B2_DMZ
  * vlan 310 name B2_VOIP

  * vlan 311 name B3_EU_F0
  * vlan 312 name B3_EU_F1
  * vlan 313 name B3_WIFI
  * vlan 314 name B3_DMZ
  * vlan 315 name B3_VOIP

  * vlan 316 name B4_EU_F0
  * vlan 317 name B4_EU_F1
  * vlan 318 name B4_WIFI
  * vlan 319 name B4_DMZ
  * vlan 320 name B4_VOIP

  * vlan 321 name B5_EU_F0
  * vlan 322 name B5_EU_F1
  * vlan 323 name B5_WIFI
  * vlan 324 name B5_DMZ
  * vlan 325 name B5_VOIP

### IPv4 address for each building
* **Building 1** - 520 nodes - /22 - 172.17.64.0/22
* **Building 2** - 219 nodes - /24 - 172.17.68.0/24 (0+1024)
* **Building 3** - 188 nodes - /24 - 172.17.69.0/24 (0+256)
* **Building 4** - 175 nodes - /24 - 172.17.70.0/24 (0+256)
* **Building 5** - 200 nodes - /24 - 172.17.71.0/24 (0+256)