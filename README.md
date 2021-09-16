# VPC-Peering-AWS

A VPC peering connection is a networking connection between two VPCs that enables you to route traffic between them using private IPv4 addresses or IPv6 addresses. Instances in either VPC can communicate with each other as if they are within the same network. You can create a VPC peering connection between your own VPCs, or with a VPC in another AWS account. The VPCs can be in different regions (also known as an inter-region VPC peering connection).

Steps to create VPC Peering to Communicate between Two Instances-

```

1. Create two VPCs in your AWS Account

2. Create a VPC Peering  

3. Update the route table

4. Create a windows instance in each VPC  

5. Connect to windows instance in second VPC with windows instance in the first VPC created.

```
