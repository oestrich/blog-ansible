# Ansible for blog.oestrich.org

## Setup

Run the following commands. Make sure `deploy/hosts` is correct.

```bash
ansible-galaxy install -r deploy/requirements.yml
ansible-playbook deploy/setup.yml -l production
```
