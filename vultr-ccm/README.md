# vultr-ccm

![Version: 1.4.0](https://img.shields.io/badge/Version-1.4.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: v0.3.0](https://img.shields.io/badge/AppVersion-v0.3.0-informational?style=flat-square)

A Helm chart for Vultr's Cloud Controller Manager

**Homepage:** <https://github.com/vultr/vultr-cloud-controller-manager>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| David Dymko |  |  |

## Source Code

* <https://github.com/vultr/vultr-cloud-controller-manager>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| env | list | `[]` |  |
| image.repository | string | `"ghcr.io/goraxe-org/vultr-cloud-controller-manager"` |  |
| image.tag | string | `"0.10.6"` |  |
| imagePullSecrets | list | `[]` |  |
| tolerations[0].effect | string | `"NoSchedule"` |  |
| tolerations[0].key | string | `"node-role.kubernetes.io/master"` |  |
| tolerations[1].key | string | `"CriticalAddonsOnly"` |  |
| tolerations[1].operator | string | `"Exists"` |  |
| tolerations[2].effect | string | `"NoSchedule"` |  |
| tolerations[2].key | string | `"node.cloudprovider.kubernetes.io/uninitialized"` |  |
| tolerations[2].value | string | `"true"` |  |
| tolerations[3].effect | string | `"NoSchedule"` |  |
| tolerations[3].key | string | `"node.kubernetes.io/not-ready"` |  |
| tolerations[3].operator | string | `"Exists"` |  |
| tolerations[4].effect | string | `"NoSchedule"` |  |
| tolerations[4].key | string | `"node.kubernetes.io/unreachable"` |  |
| tolerations[4].operator | string | `"Exists"` |  |

