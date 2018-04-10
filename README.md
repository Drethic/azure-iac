Azure Infrastructure as Code (IaC)
----------------------------------

This repository contains basic Azure templates to setup different network configurations depending on requirement.

* core-network is a basic virtual network with two domain controllers in an availability set and a jump box for connecting to the VNET.
* existing-network adds two domain controllers in an availabitly set and a jump box for connecting to an existing VNET.

All work is based off scripts from [hansenms](https://github.com/hansenms/iac)