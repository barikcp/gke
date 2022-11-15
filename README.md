# gke

Steps to create cluster in GUI:

Navigation menu -> Kubernetes Engine -> Clusters -> Create -> Select Auto Pilot (Recommended) -> Give Name & Region ->
-> Select Public Cluster ->  Create


Steps to create cluster using gcloud CLI:

gcloud projects list
gcloud container clusters create <CLUSTER_NAME>  --zone "<ZONE_NAME>" --project "<PROJECT_NAME>"
E.g.
gcloud container clusters create my-gcp-k8s-1  --zone "asia-south1-b" --project "cp-project-367912"
