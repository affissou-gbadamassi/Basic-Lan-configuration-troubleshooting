# Basic LAN Configuration & Troubleshooting

## What I Built
Built two LANs using one Cisco 1941 router, two Cisco 2960 switches, and four PCs. Configured static IPv4 addresses, default gateways, and routing between both networks.

- LAN 1: 192.168.1.0/24
- LAN 2: 192.168.2.0/24

## Why I Built It
To develop hands-on networking skills in IP addressing, Cisco IOS configuration, routing, and troubleshooting.

## What Broke
- Router interfaces were initially down.
- Incorrect Cisco IOS commands caused configuration errors.
- Initial communication between LANs failed.

## How I Fixed It
- Corrected router interface configuration commands.
- Assigned gateway IP addresses and enabled the interfaces using `no shutdown`.
- Verified PC IP settings and default gateways.
- Retested connectivity using ICMP.

## How I Recovered
Restored successful connectivity within and between both LANs. Verified the results through successful ICMP tests.

## Tools & Technologies
Cisco Packet Tracer | Cisco IOS | IPv4 | Routing | ICMP

## Project Screenshots

### 1. Router Configuration and Troubleshooting
![Router Configuration](screenshots/1.png)

### 2. LAN 1 Static IP Configuration
![LAN 1 IP Configuration](screenshots/2.png)

### 3. LAN 2 Static IP Configuration
![LAN 2 IP Configuration](screenshots/3.png)

### 4. Failed Inter-LAN Connectivity Test
![Failed Connectivity](screenshots/4.png)

### 5. Successful Connectivity After Troubleshooting
![Successful Connectivity](screenshots/5.png)
