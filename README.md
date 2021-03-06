# python-client-for-vmware-cloud-on-aws

## Overview

# pyVMC
Welcome to the Python Client for VMware Cloud on AWS !

## What is the Python Client for VMware Cloud on AWS ? 
It is a Python tool developed for VMware Cloud on AWS. PyVMC was created by Nicolas Vibert and Matt Dreyer.

## What are the pre-requisites for PyVMC ?
- Python3 installed on your machine
- a VMware Cloud on AWS account

## How do I use PyVMC ?
- clone repo
- install dependencies
```
$ pip install -r requirments.txt
```
- copy config.ini.example to config.ini and add your own token
- Edit the config.ini with your own SDDC ID,  Organization (Org) ID and your access token.

## Do I need to know Python?
No! You can simply use it to consume and manage your VMware Cloud on AWS SDDC (Software-Defined Data Center). 

## Is it officially supported by VMware?
Sorry but no, this is a community-based effort. Use it at your own risk. It has extensively been tested though and we'll endeavour to fix any bugs.

## Which version of VMware Cloud on AWS has it been tested against?
Versions 1.9, 1.10, 1.11 and 1.12. I don't guarantee support with previous versions. 
I will, however, endeavour to verify compatibility as we release new versions.

## What if I find a bug or need a new feature?
Please raise it on GitHub and I will look into it.

## Where can I find documentation about VMware Cloud on AWS:
Please check the online documentation:
https://docs.vmware.com/en/VMware-Cloud-on-AWS/index.html

## Where can I find documentation about each pyVMC commands?

Initial Release:
https://nicovibert.com/2020/02/25/pyvmc-python-vmware-cloud-aws/

First main update:
https://nicovibert.com/2020/06/01/fling-update-pyvmc-1-1-release-and-a-walkthrough-through-some-python-code/

## Release Notes

This tool enables users to:

- Create and remove networks
- Create and remove groups and services, included nested groups
- Create and remove security rules on the Management and Compute Gateways.
- Request, remove and update Public IP addresses.
- Display information about Direct Connect (such as BGP AS, MTU and VPN preference)
- Show VPN statistics, 
- Show DNS Zones and Services
- Create and remove NAT rules
- Display information about SDDC and org users
- Display information about VMs in the SDDC
- Create/Read/Update/Delete (CRUD) for Distributed Firewall Rules
- Check T0 routes
- Check Internet egress interface counters
- Create/Read/Delete L2VPN


## Roadmap

Depending on demand, the following tools might be added:

- Create New Service Entry
- Show New Service Entry
- Add DHCP Relay CRUD
- Add DNS Config Config (DNS Read Only right now.)
- Add Port Mirroring CRUD
- Add IPFIX CRUD
- Update Service Read to support non-TCP/UDP based rules
- Add VPN creation

## Contributing

The python-client-for-vmware-cloud-on-aws project team welcomes contributions from the community. Before you start working with python-client-for-vmware-cloud-on-aws, please
read our [Developer Certificate of Origin](https://cla.vmware.com/dco). All contributions to this repository must be
signed as described on that page. Your signature certifies that you wrote the patch or have the right to pass it on
as an open-source patch. For more detailed information, refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License

SPDX-License-Identifier: BSD-2-Clause
