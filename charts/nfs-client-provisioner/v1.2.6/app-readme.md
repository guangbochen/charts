# nfs-client-provisioner

The [NFS client provisioner](https://github.com/kubernetes-incubator/external-storage/tree/master/nfs-client) is an automatic provisioner for Kubernetes that uses your *already configured* NFS server, automatically creating Persistent Volumes.

### ARM Deployment
For **arm** deployments set `image.repository` to `--set image.repository=ranchercharts/external_storage-nfs-client-provisioner-arm`
