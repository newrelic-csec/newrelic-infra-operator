# e2e-resources

![Version: 1.0.0-devel](https://img.shields.io/badge/Version-1.0.0--devel-informational?style=flat-square)

This chart creates E2E resources for newrelic-infra-operator

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| juanjjaramillo |  | <https://github.com/juanjjaramillo> |
| svetlanabrennan |  | <https://github.com/svetlanabrennan> |
| csongnr |  | <https://github.com/csongnr> |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| demo | object | `{"enabled":false}` | Deploy in demo mode. Make entities consume non-negligible resources so metrics can be easily observed in the dashboards. This setting only applies to resources that would negatively impact testing times if enabled by default |
| deployment | object | `{"enabled":true}` | Deploy a dummy deployment |
| fileSystemTest | object | `{"fileName":"pi.txt"}` | Variables for filesystem testing |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.3](https://github.com/norwoodj/helm-docs/releases/v1.11.3)