

# AWS Essentials

## Account Basics

## IAM
### Manage Access
#### Users
#### Groups
#### IAM Access Policies
#### Roles

### Setup
#### Security status
##### Root Access Keys
##### MFA
##### Individual IAM Users
##### Permissions

### IAM Users and Policies

## Global Infrastructure
### A Region Has
#### Availability Zones 

## VPC
### I can place Aws resources here
#### Route Tables
#### Gatways
#### Subnets

### Internet Gateway
#### Allows communication beetween VPC - Internet
#### Rules
##### 1 IGW attache per VPC
##### IGW cannot be detached while exists active resources into VPC

### Route Tables
#### Determine where network traffic is directed
#### Rules
##### Can have multiple active route tables in a VPC
##### Cannot delete a route if it has dependencies
###### Associated Subnets

### Network Access Control List (NACLs)
#### Optional security layer
#### Acts as a firewall
#### Stateless
#### Can potentially block the communication
#### Rules
##### one Subnet -> one NACL
##### The default NACLs allow all traffic to the default subents
##### Has Inbound
##### Has Outbound
##### Processing order
###### From lowest to highest
###### Are lazy

### Subnets
#### Subsection of a network
#### A private subnet is able to communicate with other subnet
##### Through Route Table
#### Rules
##### Must be associated with a route table
##### A **Public** subnet has a route to the internet
##### A **Private** subnet does not have a route to the internet
##### A subnet is located in one specific Availability Zone

### Availability Zones
#### High Availability
#### Fault Tolerant



## EC2
### Basic desktop computer
### Scalable computing capacity
### Is On Demand
### Components
#### AMIs
#### Instance Type
#### EBS

#### Security Group
#### RAM




## Storage Services

## Databases

## SNS

## Management Tools

## ELB

## Auto Scaling

## Route 53

## Lambda


