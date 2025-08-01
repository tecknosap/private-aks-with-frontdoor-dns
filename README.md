# Project 5: Private AKS Deployment with Azure Front Door and DNS

## Overview

This project reflects an enterprise-grade, secure application deployment strategy using private AKS clusters combined with Azure Front Door for global ingress and custom DNS with WAF.

## Business Problem Solved

Public exposure of AKS APIs and workloads invites security risks. Enterprises need private clusters combined with secure, scalable, and globally available ingress endpoints.

## What You Will Build

- Private AKS cluster with restricted API server access.
- Azure Private DNS zones for cluster internal name resolution.
- Azure Front Door configured with custom domain and Web Application Firewall (WAF).
- Helm-based application deployment with strict RBAC and network policies.

## Enterprise Impact

- Dramatically reduces attack surface with private cluster networking.
- Ensures secure and performant global user access.
- Complies with enterprise security and governance standards.

## Step-by-Step

1. Provision private AKS cluster and associated private DNS zones.
2. Set up Azure Front Door with custom domain and enable WAF.
3. Deploy application using Helm charts.
4. Apply Kubernetes RBAC and Network Policies.
5. Validate ingress via Front Door with TLS and WAF protection.

## Prerequisites

- Azure subscription
- Familiarity with AKS, Helm, and Azure networking

## References

- [Azure Private AKS](https://learn.microsoft.com/en-us/azure/aks/private-clusters)
- [Azure Front Door Service](https://learn.microsoft.com/en-us/azure/frontdoor/)
