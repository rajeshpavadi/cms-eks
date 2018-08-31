# Cloudformation to launch EKS cluster

## Prerequisites

3 - SubnetIds.
1 - SecurityGroupId.

## Steps to launch

1. Edit config.json with appropriate values.
2. Execute sh run.sh.

## Description

Cloudformation will launch EKS cluster with its Iam Role.

## Outputs 

Clouformation will give ApiEndPoint as output we can use this to configure kubectl. 

Getting Started with Amazon EKS https://docs.aws.amazon.com/eks/latest/userguide/getting-started.html .

