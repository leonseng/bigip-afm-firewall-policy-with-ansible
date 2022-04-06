# BIG-IP AFM Firewall Policy Configuration Automation With Ansible

This repository demonstrates the automation of firewall policies configuration on BIG-IP Advanced Firewall Manager (AFM) using Ansible.

F5 provides two Ansible collections [`f5networks.f5_modules`](https://clouddocs.f5.com/products/orchestration/ansible/devel/f5_modules/getting_started.html) and [`f5networks.f5_bigip`](https://clouddocs.f5.com/products/orchestration/ansible/devel/f5_bigip/install_f5_bigip.html) to interact with the configuration objects on BIG-IP:

The repository will cover two different approaches to manage the firewall policies on the BIG-IP:
1. [Imperative REST API calls with `f5networks.f5_modules` collection](./f5_modules)
1. [Declarative approach with `f5networks.f5_bigip` collection](./f5_bigip)
