# Secure Network Infrastructure for a Professional Environment

This project represents our team’s effort in designing a robust, secure, and scalable network infrastructure tailored for a professional setting. Our objective was to create a network that balances simplicity with advanced functionality, ensuring both ease of management and stringent security measures.

## Project Overview

1. **Structured Network Topology**: We implemented a hierarchical tree structure over a star topology to allow better segmentation and flexibility. Using VLANs, we organized the network to improve traffic management, enhance security, and provide a strong foundation for scalability.

2. **Security Protocols and Policies**: Security was prioritized at each level of design:

   - **VLAN Segmentation**: To isolate departments and secure internal communications.
   - **Firewall Strategy and ACLs**: Extended ACLs are used internally for detailed access control, while firewalls protect the network perimeter.
   - **Azure Backup**: A cloud-based backup server on Azure ensures data protection and recovery capabilities.

3. **Protocol Integration**: Each protocol was chosen for its unique benefits in enhancing stability, security, and efficiency:

   - **HSRP** for failover redundancy,
   - **DHCP Snooping** to prevent unauthorized access,
   - **OSPF** for dynamic routing, and
   - **EtherChannel** for combined bandwidth and redundancy.

4. **Scalability**: Our design supports seamless growth. VLANs, combined with a flexible IP addressing scheme, enable straightforward integration of new departments and devices as the organization expands.

5. **Access Control**: A daily rotating password protocol for admin access adds an additional layer of security, complemented by role-based access to ensure that each user has the appropriate level of privilege.

This project has successfully addressed the client’s needs for a secure, efficient, and future-ready network, and we take pride in delivering a solution that is both comprehensive and adaptable.
