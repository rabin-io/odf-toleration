# ODF Toleration
Add toleration for the "non-ocs" taints to the OpenShift Data Foundation pods
based on the codes found in [RedHat KB6408481 article](https://access.redhat.com/articles/6408481).

# Usage

Run the playbook first with `-C` so you could see what the playbook will change, and if there anything needed to be tweaked, as the playbook might remove pre-existing config which it not aware of.

```sh
ansible-playbook config-odf.yaml --diff [-C]
```
