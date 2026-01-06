# Execution Environments

This repository contains YAML definitions for various Ansible Execution Environments (EEs)

## Default EE

* Definition file: `execution-environment-default.yml`
* Description: multi-purpose EE
* How to built:
  ```
  ansible-navigator builder build -t ee_default  -f execution-environment-default.yml
  ```
## Kubespray EE
* Definition file: `execution-environment-kubespray.yml`
* Description: special EE that includes https://github.com/kubernetes-sigs/kubespray as a collection
* How to built:
  ```
  ansible-navigator builder build -t ee_kubespray  -f execution-environment-kubespray.yml
  ```
