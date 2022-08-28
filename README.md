# cookbook
Riotkit's infrastructure cookbook - how we do infrastructure. Read and do it your self! DIY!

Chapters
--------

1. Network

   1.1. Cluster-wide VPN
  
   1.2. Admin VPN
   
   1.3. TOR

   1.4. Firewall with UFW

2. Fundamental services - "Core Services"

   2.1. Setting up GIT and Password manager
   
   2.2. Using SaaS (if not using self-hosted services)

3. Creating a cluster

   3.1. Preparing a GIT repository and credentials

   3.2. Primary node

   3.3. Secondary nodes

4. Getting started with cluster

   4.1. Theory - API server, scheduler, declarations, nodes

   4.2. Understanding networking with Flannel and Wireguard

   4.3. kubectl

   4.4. ArgoCD

5. Managing cluster declaratively

   5.1. Namespaces
   
   5.2. PVCs

   5.3. Secrets

6. Observability

   6.1. Victoria Metrics

   6.2. Uptime Kuma and Uptime Robot

   6.3. InfraCheck

   6.4. Alerting from Grafana

7. Security

   7.1. Network Policies

   7.2. Egress traffic with TOR
   
   6.3. Seccomp and AppArmor

8. Sending e-mails

   8.1. Setting up a mail relay

9. Extras

   9.1. Synchronizing volumes with external S3-compatilbe storage (volume-syncing-controller)
   
   9.2. Cloning git repositories inside Kubernetes Pods on pod initialization (git-clone-controller)

10. Backup

   10.1. Setting up Backup Repository
  
   10.2. Using backup-maker

   10.3. Additional note about volume-syncing-controller
   


