# Cisco VLAN Router-on-a-Stick Lab

## Overview

This project is a Cisco Packet Tracer network lab demonstrating VLAN segmentation and inter-VLAN routing using the Router-on-a-Stick method.

The goal of this lab is to configure multiple VLANs, establish trunk communication between switches and router, and enable communication between different network segments.

## Topology

The network consists of:

- Cisco Router
- Cisco Switches
- Multiple VLANs
- End devices (PCs)

## VLAN Configuration

| VLAN | Network | Default Gateway |
|------|---------|-----------------|
| VLAN 10 | 10.0.0.0/24 | 10.0.0.1 |
| VLAN 20 | 20.0.0.0/24 | 20.0.0.1 |
| VLAN 30 | 30.0.0.0/24 | 30.0.0.1 |

## Implemented Features

- VLAN creation and assignment
- Access port configuration
- 802.1Q trunk configuration
- Router-on-a-Stick implementation
- Inter-VLAN routing
- Network connectivity testing

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS CLI
- VLAN
- IEEE 802.1Q
- Inter-VLAN Routing

## Verification

The network was tested using:

- Ping between devices
- Interface status verification
- VLAN and trunk verification commands

## File

`Cisco-VLAN-Router-on-a-Stick.pkt`

Cisco Packet Tracer simulation file containing the complete topology and configuration.
