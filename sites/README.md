# Site Deployments

To create a new `Site` deployment, add a file such as this to the `deployments` folder and merge into the `main` branch.

```
apiVersion: deploy.ethzero.cloud/v1
kind: Site
metadata:
  name: atl-bldg-1
spec:
  clusterName: atl-bldg-1
  nodeImage: Ubuntu 20.04
  numMasters: 1
  numWorkers: 0
  runWorkloadOnMasters: true
```
