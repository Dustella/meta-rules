# meta-rules

personal rules for clash meta

example `proxy-provider.yaml`

```yaml
rule-providers:
  direct-apps:
    type: http
    behavior: domain
    url: " https://cdn.jsdelivr.net/gh/dustella/meta-rules/rules/direct-apps.yaml"
    path: ./ruleset/direct-apps.yaml
    interval: 86400
```

example `ruleset.yaml`

```yaml
rules:
  - RULE-SET,./ruleset/direct-apps.yaml,DIRECT
```
