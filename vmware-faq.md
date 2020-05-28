## You want a VM for a project?

Contact Prof. Aviv and he'll set something up for you

## What ports can I have open?

You can request a bunch of stuff via SEASCF, but ssh will be limited to only via the VPN

## What is our domain name scheme?

All VMs are named after major league baseball teams. American League team names have external IP addresses (or also internal on the 10.0.0.1/24) network. National League only have internal. 

## Why this naming scheme?

Because Prof. Aviv likes baseball.

## How to get a IP address at GW?

You need to email SEASECF

## How to get a local `mlb` net IP address?

Shoudl get one from DHCP, but you can also request a static address by contacting Prof. Aviv

## How to setup the network for `vmnet` and `mlb`?

Create a `config.yaml` in `/etc/netplan` 

```
network:
  version: 2
  ethernets:
    ens160:
      dhcp4: true
      dhcp4-overrides:
        route-metric: 100
    ens192:
      dhcp4: true
      dhcp4-overrides:
        route-metric: 200
 ```
 
 be sure to include the route-metric, otherwise preference won't be set. 
 
 
