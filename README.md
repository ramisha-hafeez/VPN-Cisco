# VPN-Cisco
Enterprise-Scale Multi-Site Network with VPN &amp; Security Architecture
This project simulates an enterprise-grade network using Cisco Packet Tracer, complete with IPsec VPN tunnels, SYSLOG integration, and multi-site connectivity. Designed to support six segmented network zones, each with its own routing logic and security framework, the architecture leverages dynamic protocols and firewall policies to ensure scalability, privacy, and resilience.
##  Project Objectives
- Design a **multi-site star topology** linked via a simulated ISP backbone.
- Configure and validate **IPsec VPN tunnels** between branch routers.
- Implement **DHCP**, **DNS**, **NAT**, and **ACLs** to manage traffic flow and security.
- Enable centralized **SYSLOG monitoring** for real-time network visibility.
- Test fault tolerance and basic scalability within the topology.
## Technologies & Features Used
- **Cisco Packet Tracer 8.x**
- **IPsec VPN tunnels**
- **ACLs for traffic control**
- **DHCP, DNS & NAT services**
- **SYSLOG configuration**
- **RIP for dynamic routing**
- **Star topology with layered segments**
##  Setup & Simulation
Open `vpn-project.pkt` in Packet Tracer and follow the steps in `docs/setup-guide.md` to:
1. Power on all devices and verify interface IPs.
2. Establish RIP-based dynamic routing.
3. Initiate VPN tunnels using ISAKMP and IPsec policies.
4. Configure SYSLOG servers on routers.
5. Simulate network communication between zones.




