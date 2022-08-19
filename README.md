# Apply

1. Clone repo
2. Add required files to kustomize/app-policy
3. Modify channel path in acm-config/subscription.yaml
4. oc login to ACM cluster
5. oc apply -f acm-config/subscription.yaml

# Based upon

https://cloud.redhat.com/blog/generating-governance-policies-using-kustomize-and-gitops

https://github.com/stolostron/grc-policy-generator-blog

https://docs.openshift.com/container-platform/4.11/logging/cluster-logging-deploying.html#cluster-logging-deploy-cli_cluster-logging-deploying