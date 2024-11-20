# ATCRepo-poc


Prerequisites: Tools (Terraform, Docker, kubectl, Helm).

Deployment Steps:
Build and push the Docker image.
Provision the infrastructure using Terraform.
Apply Kubernetes manifests using kubectl.
Set up Prometheus for monitoring.

Verification:
Access the web app via the LoadBalancer IP.
Check Prometheus metrics endpoint and cluster monitoring.
