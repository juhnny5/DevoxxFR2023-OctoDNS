# Démo 1

## Commandes

Côté OctoDNS :

```shell
octodns-validate --config-file=./1demo/config/config.yml
octodns-sync --config-file=./1demo/config/config.yml --force
octodns-sync --config-file=./1demo/config/config.yml --force --doit
```

Côté PowerDNS :

```shell
pdnsutil list-zone totozone.com
```
