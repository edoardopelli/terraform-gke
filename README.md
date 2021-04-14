# Provision a GKE Cluster and deploy nginx service

Move into terraform-provision-gke-cluster folder and open terraform.tfvars file.
Change the google project_id and zone values with yours.

Then execute 'terraform init' and then 'terraform apply' (if you want you want you can run 'terraform plan' before the apply command, so you can verify what will be created).

After that you can move into terraform-deploy-nginx-kubernetes folder and run the same commands.

**This code is not for a productive environment**
