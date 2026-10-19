# Home LAN with Cisco Packet Tracer

A Computer Networks coursework project by Ghazal ALsharif. The original Packet Tracer project is included as `home-lan.pkt`.

## Topology

Two PCs and two laptops connect to a Cisco 2960-24TT switch through copper straight-through Ethernet cables. The devices form a star topology on one IPv4 subnet.

| Device | IPv4 address | Subnet mask |
| --- | --- | --- |
| Home PC | 192.168.1.1 | 255.255.255.0 |
| Game PC | 192.168.1.2 | 255.255.255.0 |
| Laptop 1 | 192.168.1.3 | 255.255.255.0 |
| Laptop 2 | 192.168.1.4 | 255.255.255.0 |

## Work demonstrated

- Connecting end devices to separate switch ports.
- Assigning static IPv4 addresses on the same subnet.
- Configuring a switch hostname and basic console/enable access in a simulation.
- Saving the switch configuration.
- Testing connectivity with ping.

The submitted report records three ping tests to the Home PC, each with four replies and zero packet loss. These results are from the coursework report and have not been independently rerun for this repository.

## Open the project

Open `home-lan.pkt` in Cisco Packet Tracer. The exact authoring version is not documented. This is a simulated educational network, not a production configuration. The original assignment/report is omitted to avoid publishing student identifiers and assessment material.
