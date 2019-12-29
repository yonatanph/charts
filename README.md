# Check Point Helm Charts

## Overview

This repository hosts Check Points [Helm Charts](https://helm.sh) for deploying applications to [Kubernetes](https://kubernetes.io/).

The `stable` directory contains the Helm chart source files, while the `repo/stable` directory contains the packaged Helm chart binaries.  

To add the stable repo to local repository list run the following command : 
```
helm repo add stable https://github.com/yonatanph/charts/tree/master/repository/stable
helm repo add stable https://raw.github.com/yonatanph/charts/tree/master/repository/stable
helm repo add stable https://raw.githubusercontent.com/yonatanph/charts/tree/master/repository/stable
```

## Install Helm

Please install [Helm](https://helm.sh) as explained in their [documentation](https://helm.sh/docs/intro/install/#scrollpane).

Once Helm is set up properly, add the repo as follows:

```console
$ helm repo add checkpoint https://checkpoint.github.io/helm-charts
```
