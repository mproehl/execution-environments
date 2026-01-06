# Execution Environments

This repository contains YAML definitions for various Ansible Execution Environments (EEs)

## `execution-environment-default.yml`

* Multi purpose EE
* How to built:
  ```
  ansible-navigator builder build -t ee_default  -f execution-environment-default.yml
  ```
## `execution-environment-kubespray.yml`

* A special EE that includes https://github.com/kubernetes-sigs/kubespray as a collection
* How to built:
  ```
  ansible-navigator builder build -t ee_kubespray  -f execution-environment-kubespray.yml
  ```
