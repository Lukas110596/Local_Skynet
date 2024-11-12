Local Skynet 🌐

Local Skynet is a robust and user-friendly security and network management solution that integrates various services into a centralized system. It aims to improve network security and operational oversight while prioritizing energy efficiency and performance. Designed to be versatile, Local Skynet provides automated security features for all user levels, from beginners to advanced users.
Project Overview

Local Skynet is built to:

    Enhance Network Security: By integrating tools like deep packet inspection, intrusion detection/prevention, and ad blocking (Pi-Hole).
    Streamline Network Management: Through a centralized dashboard and VPN support.
    Customize User Experience: Allowing users to add or configure services via Docker containers, supporting both plug-and-play functionality for beginners and advanced configurations for experienced users.

Key Features

    VPN Access: A Wireguard VPN server enables remote access to local network resources and services.
    Dashboard: A customizable dashboard displays Google search, weather, and system statistics (CPU, RAM).
    Ad Blocking: A Pi-Hole service acts as a local DNS, filtering out ads and tracking.
    Modular Services: Additional features include reverse proxy, dynamic DNS, port scanning, IDS/IPS, and more.

Target Audience

    Non-technical users needing simple setup
    Advanced users who want detailed control over network configurations

Technical Details
Stack and Tools Used

    Containerization: Docker with Docker Compose for service orchestration
    Network Security: Wireguard VPN, Traefik reverse proxy, Pi-Hole, CrowdSec for intrusion prevention
    Development and Management: Portainer for container management, DuckDNS for dynamic DNS
    Programming Language: Primarily JavaScript for custom scripts and dashboards
    API Integrations: Includes pwnedpasswords API for password security, Google DNS, and Let's Encrypt for automatic SSL certificate generation

Development Requirements

    MUST: Core services like Traefik, Pi-hole, NGINX, and Wireguard, with management via Docker Compose
    SHOULD: Services like Ansible, CrowdSec, and GUI management tools for containers
    COULD: Advanced features such as DPI (Deep Packet Inspection) and automated certificate generation


Credits

    Mihailo Vucinic
    Tristan Westreicher
    Julian Wildauer
    Lukas Schertler
