# DEVOXX 2023 - Speaker Notes

Speaker: **Julien BRIAULT**
Date: **07/04/2023**

---

## Commands

Mise en place de l'environnement PowerDNS :

```shell
multipass launch --name powerdns --cloud-init .cloud-init.yaml
multipass shell powerdns
```

A lancer avant la démo :

```shell
source venv/bin/activate
source .env
```

Commandes utiles pour la démo :

```shell
pdnsutil list-zone totozone.com
dig @ns-1821.awsdns-35.co.uk. test.totozone.com
```
