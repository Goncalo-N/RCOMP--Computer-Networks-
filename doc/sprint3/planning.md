RCOMP 2021-2022 Project - Sprint 3 planning
===========================================
### Sprint master: 1201525 ###

### Sprint's backlog

-------------------------------------------------------------------
| Task |  Task description |
|------|---------------------------------------------------------------------------------------------------------
|T.3.1 | Update the building1.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 1.
|T.3.2 | Update the building2.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 2. Final integration of each member’s Packet Tracer simulation into a single simulation (campus.pkt).
|T.3.3 | Update the building3.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 3.
|T.3.4 | Update the building4.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 4.
|T.3.5 | Update the building5.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint forbuilding 5.

### Tasks assignment

  * 1181027 - T.3.1
  * 1201654 - T.3.2
  * 1201525 - T.3.3
  * 1200611 - T.3.4
  * 1200801 - T.3.5

-------------------------------------------------------------------

### OSPF Area Ids

-------------------------------------------------------------------
| Building | Area ID |
| -------- | ------- |
| BackBone |    0    |
|     1    |    1    |
|     2    |    2    |
|     3    |    3    |
|     4	   |    4    |
|     5    |    5    |

### VoIP service

VoIP service decisions for all buildings.

-------------------------------------------------------------------
|Building|  ITS Server |Phone Number|
|:------:|:-----------:|:----------:|
|    1   |172.17.66.65 |    0001    |
|    1   |172.17.66.65 |    0002    |
|    2   |172.17.68.241|    1001    |
|    2   |172.17.68.241|    1002    |
|    3   |172.17.69.225|    2001    |
|    3   |172.17.69.225|    2002    |
|    4   |172.17.70.241|    3001    |
|    4   |172.17.70.241|    3002    |
|    5   |172.17.71.225|    4001    |
|    5   |172.17.71.225|    4002    |

### DNS server to establish a DNS domains tree

DNS configurations for all buildings.

-------------------------------------------------------------------
|Building|     IPv4    |          DNS Domain         |         DNS Name Server        |
|:------:|:-----------:|:---------------------------:|:------------------------------:|
|    1   | 172.17.65.2 |      rcomp-21-22-dgg-g3     |      ns.rcomp-21-22-dgg-g3     |
|    2   |172.17.68.226|building-2.rcomp-21-22-dgg-g3|ns.building-2.rcomp-21-22-dgg-g3|
|    3   |172.17.69.194|building-3.rcomp-21-22-dgg-g3|ns.building-3.rcomp-21-22-dgg-g3|
|    4   |172.17.70.226|building-4.rcomp-21-22-dgg-g3|ns.building-4.rcomp-21-22-dgg-g3|
|    5   |172.17.71.194|building-5.rcomp-21-22-dgg-g3|ns.building-5.rcomp-21-22-dgg-g3|