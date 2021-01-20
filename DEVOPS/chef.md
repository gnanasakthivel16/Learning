### Learning  Chef:

https://cognizant.udemy.com/course/learn-chef/learn/

# 1. Introduction 

Chef Infra(Iac) is an automation framework to build the infrastructure.

# 2. Objective: 
* Imperative vs Declarative. Chef is declarative
* push vs pull . push eg: Ansible & saltstack and Pull -eg: Chef and Puppet
* Idempotent  and convergence 

# 3. Understanding Chef 

Chef various services
* Chef Infra
* Chef Inspec
* Chef Habitat
* Chef Automate

Chef is developed using "Ruby". It was introduced in 2008 as OPS Code and later changed to Chef.
# It has 2 deployment model:
  * Client and server
  * standalone or zero 
  
 # key features:
  * Declartive
  * Increase productivity
  * consistent Delivery
  * Simplicity
  * High scalable
  
  # Chef architecute
  
  Divided into 3 major sections
  * Work station
  * Chef server
  * Chef client
  
  
 # 4. Setup 
 
  Chef provides 3 different offerings.
  
  * Chef server open source
  * chef Enterprise - on premises
  * Chef Enterprise 0 Multi tentant
  
  ### Pre-requisites:
  
  * Network connectivity
  * Persisent FQDN
  * System Requirement
  * support Platform
  * Firewall setting
  * Time sync
  
  ### hosting the chef environment we needto sign up. And create an Organization. Organisation is  the place all the chef content are stored.
  
 # 5. Chef Workstation
 
 Chef workstation is location place where we will develop the chef  script using the chef Development Kit(CDK). 
 
 ### pre-reuisites
 * Network connectivity
 * System Requirement
 * Supported Platform
 * File space
 
 
 To start the chef workstation, first we need to install the CDK.
 
 # 6 Demo - Workstation vm provisioning in AWS EC2 
 
 # 7. Demo - CDK setup 
 * setup hostnamectl set-hostname workstation.example.com
 * copy the chef DK  url from chef dowload site
 * perform download in centos using wget <ur>
 * Install the chef
 * validate the chef version using "chef -version"
 * Validate the Knife ersion using "kinife -version"
 
  
  # 8 Setup Chef Client
  * Netwrok connectivity
  * File system space
  * Persistent Hostname
  * Supported platform
  * Time Sync- using NTP
  * System Requirement - no specific
  
  Chef client can be installed by
  * Chef Client - install package
  * knife bootstrap method
  
  
  # 9 
  
  # Chef Concept
  # 10 Chef Architecture
  
  3 major components:
  * Chef Workstation - where we will develop our recepies and cookbook. OT communiate to server via public RSA key.
  * Chef Server - is a centre repository. we are all the information are stored.
  * Chef Client - it installed in all the node such as VM, Cloud, Network devices. It will establish a communication via RSA public keypair to connect the server.( OHIA command)
  
  ### Chef Terminologies
  * Resoruces
  * Receipe - combination of resources
  * Cookbook - Combinaion of receipe
  * runbook - Combniation of cookbook.
  
  # 11 Chef Resources
  
  Fundamental building block of chef architecture
  ### 2 kinds of resources:
  * Built in
   * File 
   * User file etc -- refer to doc
  * Custom resoruse - from 12.5
  
  # 12 Demo - Chef Resources
  
  ### doc.chef.io
  
  # 13 Chef DSL
  
  ### DSL - Domain Specification Language
  
   6 Different types
   * Resource Type/ Resource Name
   * Start Block
   * Attribute Name/Atrribute Value 
   * Action/Action Value
   * End 
   * # - Comment line
   
   ### Example Apache Application
   
  
  # 14 
  
  
  
