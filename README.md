# Packet Tracer Network Lab Challenges - Solutions

In this document, I provide solutions to the challenges presented in the Packet Tracer network lab. These challenges cover various aspects of network configuration, troubleshooting, and security. Let's dive into each challenge and its solution.

## Challenge 01: Find the Username and Password for Switch CLI

### Solution:
- The username and password for accessing the switch CLI are as follows:
    - Username: **net**
    - Password: **game**

## Challenge 02: Experience MAC Learning and Switch Forwarding Logic

### Solution:
1. Access the Cisco Catalyst 2960 switch CLI.
2. Configure VLANs and assign interfaces to VLANs.
3. Observe the MAC learning process by monitoring MAC address tables.
4. Verify switch forwarding logic by testing connectivity between devices in different VLANs.
5. Secret key for the next lab: **hackerman** and **failure**.

## Challenge 03: Verify VLAN Configurations

### Solution:
1. Access the switch CLI.
2. Use `show vlan` to view VLAN configurations.
3. Troubleshoot individual VLAN configurations.
4. Ensure VLANs are correctly configured.

## Challenge 04: Configure Hostname on the Switch

### Solution:
1. Access the switch CLI.
2. Enter privileged EXEC mode: `enable`
3. Enter global configuration mode: `configure terminal`
4. Set the hostname: `hostname ssh`

## Challenge 05: Troubleshoot Interface Issues

### Solution:
1. Access the switch CLI.
2. Use `show interfaces status` to check interface status.
3. Troubleshoot based on line status and protocol status.
4. Focus on late collision counter.

## Challenge 06: Correct IP Address Configurations

### Solution:
1. Access the switch CLI.
2. Use `show vlan` to view configured VLANs.
3. Use `show interface vlan <vlan_id>` to verify IP address configurations.
4. Correct IP address assignments according to VLANs.

## Challenge 07: Troubleshoot Duplex Mismatch

### Solution:
1. Access the switch CLI.
2. Use `show interfaces status` to check duplex status.
3. Correct duplex mismatches (if found).
4. Test network connectivity.

## Challenge 08: Configure SSH

### Solution:
1. Access the switch CLI.
2. Verify hostname and domain configurations.
3. Check SSH configuration.
4. Generate SSH keys (if needed).
5. Test SSH connectivity.

## Challenge 09: Change Timeout Configuration

### Solution:
1. Access the switch CLI.
2. Enter privileged EXEC mode: `enable`
3. Enter global configuration mode: `conf t`
4. Change the timeout configuration:
   - For console line: `line con 0`, `exec-timeout 10 0`
   - Verify with `show running-config`.

## Challenge 10: Verify VLAN Functionality

### Solution:
1. Access the switch CLI.
2. Check VLAN configuration: `show vlan`.
3. Verify trunk interfaces: `show interface trunk`.
4. Configure trunk interfaces if needed.
5. Check interface status: `show interface status`.
6. Test VLAN functionality.

## Read_Me File:

The Read_Me file contains solutions to the challenges presented in this document. It provides step-by-step instructions for configuring and troubleshooting network devices using Cisco Packet Tracer. Feel free to explore and learn from these challenges! 🚀🔧🔍
