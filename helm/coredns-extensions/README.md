# coredns-extensions

Extra resources for CoreDNS

**Homepage:** <https://github.com/giantswarm/coredns-extensions-app>

## Source Code

* <https://github.com/giantswarm/coredns-extensions-app>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| name | string | `"coredns-extensions"` |  |
| serviceType | string | `"managed"` |  |
| vpa.enabled | bool | `true` |  |
| vpa.controlledResources[0] | string | `"memory"` |  |
| vpa.minAllowed.cpu | string | `"50m"` |  |
| vpa.minAllowed.memory | string | `"150Mi"` |  |
| vpa.maxAllowed | object | `{}` |  |
