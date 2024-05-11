# Terraform to Bulding Kubernetes Cluster using EC2 instances

I build this project to create my own lab for [Kuberntes](https://kubernetes.io/) cluster on AWS cloud using EC2 instances. I found [Terraform](https://www.terraform.io) is best tool to create my K8S lab fastly with one command 🚀.
<p align="center">

![Terraform](https://i.imgur.com/PuS3rmb.png)
</p>

## Terraform Resources Used
- EC2
  - One Master Node
  - Two Worker Node (can be increased)
- VPC
  - Public Subnet
  - Internet Gateway
  - Route Table
  - Security Group
- S3 Bucket

<hr>

## How Will the Kubernetes Cluster Be Built?
The goals is to build K8S cluster with one master node and two worker nodes.
<br>
