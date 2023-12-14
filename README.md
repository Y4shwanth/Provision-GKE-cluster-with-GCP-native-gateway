# Provision-GKE-cluster-with-GCP-native-gateway

This repo consists of Kubernetes configuration files that are used to set-up sandbox and production Environments in GKE
Cluster_mode: Standard
External_connectivity_stack: Gateway(gke-l7-global-external-managed and gke-l7-rilb) and httproutes(with URLRewrite features).
SSL_certificates: Google managed for global external load balance, Let's Encrpyt for regional internal load balancer.
DNS: AWS R53
