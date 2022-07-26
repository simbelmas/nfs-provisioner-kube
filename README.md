# nfs-provisioner-kube
nfs-provisioner client deployment on kubernetes using kustomize.

Bare template nfs-provisioner.yaml can be used in external kustomization.

Need to already have an nfs server.
Uses podSecurityPolicy.

Defines storage class with retain policy.