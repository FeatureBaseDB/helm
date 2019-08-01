# Pilosa Cluster Helm Chart (Alpha)

This repository contains the Helm chart for Pilosa distributed index. The open source project is at: https://www.pilosa.com.

This chart is being tested and is not recommended to be used in production.

We are looking for feedback about the chart. If you have fixes or improvements to this Helm chart, you can file an issue at https://github.com/pilosa/helm or send an email to dev@pilosa.com.

## Prerequisites

- helm v2

## Packaging

```
$ helm package pilosa
```

Creates the `pilosa-${VERSION}.tgz` package.

## Install

```
$ helm install --name my-release --set persistentVolume.enabled=true ./pilosa-0.1.1.tgz
```

## Contact


## License

```
Copyright 2019 Pilosa Corp.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
