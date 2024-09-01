---
title: "<b>Building a High Availability Cluster with HAProxy, Keepalived, and Docker: A Step-by-Step Guide
</b>"
excerpt: "<i>Build a high availability cluster with HAProxy, Keepalived, and Docker. Learn setup and deployment for reliable, scalable applications.</i>
<br/><a href='https://github.com/SpaaceCadet/Docker-compose-HAProxy-Keepalived'><img  width='600' height='300' src='/images/247.PNG'></a>"
collection: portfolio

---
This project aims to create a highly available cluster using HAProxy and Keepalived in a containerized environment with Docker Compose.

- **Network Configuration:** The cluster operates under a network bridge with the subnet `10.0.0.0/24`.
  
- **VRRP (Virtual Router Redundancy Protocol):** Keepalived uses VRRP behind the scenes to assign a virtual IP address to both HAProxy nodes, ensuring high availability.

- **HAProxy:** HAProxy (High Availability Proxy) is used to balance traffic across backend servers and perform health checks.
<br>
<a><img src='/images/247.png'></a>
<br>

<a href='https://github.com/SpaaceCadet/Docker-compose-HAProxy-Keepalived'>For more details</a>

