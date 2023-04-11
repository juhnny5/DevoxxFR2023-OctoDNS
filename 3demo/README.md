# Démo 3

## Commandes

Côté OctoDNS :

```shell
octodns-validate --config-file=./3demo/config/config.yml
octodns-sync --config-file=./3demo/config/config.yml --force
octodns-sync --config-file=./3demo/config/config.yml --force --doit
```

Côté Route53 :

```shell
aws route53 list-resource-record-sets --hosted-zone-id ${AWS_ZONE_IDE} --profile talk | jq '.ResourceRecordSets[]'
```
