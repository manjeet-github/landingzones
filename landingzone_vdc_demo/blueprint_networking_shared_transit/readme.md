# blueprint_networking_shared_transit
blueprint_networking_shared_transit brings the foundation of tranit network in a hub-spoke topology. This current blueprint implements only the vpn transit, but could easily be extended to implement an ExpressRoute option. 

# Overall architecture
The following diagram shows the environment we are deploying in this blueprint: 
![Transit](https://github.com/aztfmod/landingzones/blob/master/landingzone_vdc_demo/docs/diagram-transit.png)


## Capabilities

 - Virtual network
    - Virtual network address space
    - DNS Servers 
    - Subnets
        - Subnet address space
        - Network Security Groups 
        - Virtual Network Service Endpoints
        - NSG diagnostics
    - Attach NSG to subnet
    - Virtual network operations logs and auditing
 - Virtual network peering object with shared_networking virtual network
 - Virtual network gateway
 - Public IP address
    - Diagnostics settings


# Contribute
This is a demo environement but pull requests are welcome to evolve the framework and integrate new features!