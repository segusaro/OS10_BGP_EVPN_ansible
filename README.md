# Dell EMC Networking OS10 BGP EVPN VXLAN multi-site with Ansible automation
This example shows configuration for 2 sites with BGP EVPN VXLAN for Layer 2 extension and Assymetric IRB (Integrated Routing and Bridging) using Ansible:
* Underlay protocol is eBGP
* Overlay protocol is eBGP
* EVI is manually configured
* VLT is configured for LAG to server or other L2 switches
* Anycast gateway is configured for default gateway redundancy 
* Ansible is used for configuration management and automation
* Swicth 'show running-configuration' are available in configs folder 
* Some Dell EMC Networking Ansible Roles orgignally available on Ansible Galaxy was modified to add additional variables for UFD, BGP EVPN scenario. These roles are provide "AS IS". For original Dell Networking Ansible Roles visit https://galaxy.ansible.com/Dell-Networking
* dell-vxlan Ansible Role is written from a scratch and implements only nesessary. It was tested for limited configuration scenario. This role is provided "AS IS".

Network Topology
![Network Topology](/OS10_BGP_EVPN_ansible/Topology.png)
