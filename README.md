# [ansible-builder](https://ansible.readthedocs.io/projects/builder/en/stable/)

Used for creating an ansible execution environment

### Execution environment
#### Components
- The environment consists of the following components
  1. Ansible Core
  2. Ansible Runner
  3. Ansible Collections

#### How is it created
- First we start by downloading `ansible-builder` via [`pip3 install ansible-builder`](https://pypi.org/project/ansible-builder/)
- Next we create the `execution-environment.yml` which specifies the aforementioned components
- Invoking the command [`ansible-builder create --verbosity 3`](https://ansible.readthedocs.io/projects/builder/en/stable/usage/) results in generating both the `Dockerfile` and the build `Context` directory