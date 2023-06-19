Ansible 2.10+ has shared collection support, but Ansibl2 2.9 (which is version of Ansible Tower) does not.

to use these roles set your roles/requirements.yml:

roles:
  - src: https://github.com/sentrium/ansible-shared-roles.git
