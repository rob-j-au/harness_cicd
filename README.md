### Harness Kubernetes Manifests

Example of manifests for use in a Harness CD that can be shared between all deployed services (using Harness variable interpolation)

**Non-shared**

Runtime Environment Variables are required to be set as appropriate for each service in:

[values.yaml](values.yaml)

[manifests/config-map.yaml](manifests/config-map.yaml)