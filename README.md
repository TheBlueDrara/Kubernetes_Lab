# Nginx k8s deployment

## Overview

A sinlge manifest file that contains all the resources to deploy an nginx deployment

## Prerequisites

- configure a nfs server in the correct network as your cluster
- k3s or k8s

## Features

- PV, PVC, ConfigMap, Custom StorageClass and Deployment configs in a single file.

## How to use 

Run the deployment on your k8s cluster

```
kubectl apply -f deployment.yaml
```

Now check if the webserver works

```
curl <Pod_Ip_Address>:1234
```

All done!

## Task

you can find the task [here](TASK.md)


## Contributors

you can find the contributors [here](CONTRIBUTORS.md)


#### Daily Warhammer 40K Quote

```
"I do not grieve the fallen.
 I carry their legacy in this vial.
 In death, they serve the Emperor still."

— Apothecary Garran Vos, Deathwatch, Jericho Reach
```

