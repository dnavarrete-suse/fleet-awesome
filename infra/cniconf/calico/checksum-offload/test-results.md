# Testing
## Content

- Description :white_check_mark: 
- Requirements :heavy_exclamation_mark:

Observations: Requirements missing

## Deployment

:heavy_exclamation_mark:

Observations:

```
Unable to continue with install: HelmChartConfig "rke2-calico" in namespace "kube-system" exists and cannot be imported into the current release: invalid ownership metadata; label validation error: missing key "app.kubernetes.io/managed-by": must be set to "Helm"; annotation validation error: missing key "meta.helm.sh/release-name": must be set to "dnav-qa-infra-cniconf-calico-checksum-offload"; annotation validation error: missing key "meta.helm.sh/release-namespace": must be set to "kube-system"
```

The "rke2-calico" HelmChartConfig exists on a brand new Downstream cluster.

## Readiness

:heavy_minus_sign:

## Errors

:heavy_minus_sign:
