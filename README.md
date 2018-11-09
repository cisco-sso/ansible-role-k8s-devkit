# [DEPRECATED] Kubernetes KDK (Kubernetes Development Kit)

# This repository no longer maintained.  Please use the dockerized open-source version at https://github.com/cisco-sso/kdk

**ansible-role-k8s-devkit**

Configures a machine with tools for Kubernetes, Helm and Docker DevOps.

## Supported Machine Targets

- [k8s-devkit](https://github.com/cisco-sso/k8s-devkit)

## Requirements

- Ansible 2.4.3

## Role Variables

(TODO)

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

(TODO)

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Ansible Galaxy Requirements Usage Example

```yaml
- name: ansible-role-k8s-devkit
  src: git+https://github.com/cisco-sso/ansible-role-k8s-devkit
  version: master
```

## Ansible Local Playbook Usage Example

```yaml
- hosts: local
  roles:
    - ansible-role-k8s-devkit
```

## Ansible Local Inventory Example

```
[local]
localhost ansible_connection=local
```

## License

```
Copyright © 2018 Cisco Systems, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
