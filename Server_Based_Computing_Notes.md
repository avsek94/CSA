### EC2 (Elastic Cloud Computing)
=========================================================

Software based Platform.

Software vs Hardware based
Scalability and elasticity.
Ability of creating a test environment as per need.

To create an EC2 instance we have a call to EC2 Api.


There is a virtual machine import wizard to import virtual machine images.


1. What is bootstraping in AWS ?




AMI (Amazon Machine Image):
A Preconfigured package (templete) required to launch and EC2 instance; includes an:
  * Operating systems
  * Software
  * Other required settings (root storage type & virtualization type)

AMI comes in three main categories
  * Community AMIs:
      * Free to use
      * Generally with these AMIs you will just get the OS you want.

  * AWS Marketplace AMIs
      * Pay to use
      * Generally comes packaged with additional, licensed Software

  * My AMIs
      * AMIs that you create yourself.

EC2 instance types:

Instance types describes the "Hardware" components that an EC2 instances will run on:

* Compute Power (processors/vCPU)
* Storage Options/Optimization
* Memory (RAM)
* Network Performance

Processors Features:
* AVX: highly parallel HPC workloads
* AES-NI: accelerated encryption/decryption
* Turbo Boosts: overclocking
* Transactional Synchronization (TSX) Extension - higher performance    for multi threaded transactions

Instance details and Bootstrapping:


EC2 IP Address:

* Private IP Address:
  * All EC2 instances are automatically create with a PRIVATE IP address.
  * Used for internal communication between instances inside the VPC
* Public IP Address
  * Needed if our instance have to be accessible from internet
* Elastic IP Address.
  * Dynamic Ip address which does not change.
