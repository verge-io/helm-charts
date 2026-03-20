# VergeOS Helm Charts

Helm chart repository for VergeOS Kubernetes components.

## Usage

```bash
helm repo add verge-io https://verge-io.github.io/helm-charts
helm repo update
helm search repo verge-io
```

## Charts

| Chart                                | Description                                                |
| ------------------------------------ | ---------------------------------------------------------- |
| **vergeos-node-driver**              | Docker Machine node driver and Rancher UI extension        |
| **vergeos-cloud-controller-manager** | Cloud controller for node lifecycle and load balancing     |
| **vergeos-csi**                      | CSI driver for NAS (NFS/EXT4) and Block (VM drive) storage |

## Documentation

See the [VergeOS docs](https://docs.verge.io/product-guide/tools-integrations/kubernetes-integration/) for installation and configuration guides.

## License

Copyright Verge.io. All rights reserved.
