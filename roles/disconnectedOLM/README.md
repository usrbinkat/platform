# disconnected OLM

###Purpose: This role is used for configuring the cluster operatorhub.

###Variables:
The following role specific variables are defined:
|Name|Purpose|
|----|----|
|kubeconfig_path|/root/deploy/bak/auth/kubeconfig|

###Example Playbook calling role
```yaml
---
- name: {{ ansible_name_module }} | Include olmDisconnected role
  roles:
    - olmDisconnected
```

