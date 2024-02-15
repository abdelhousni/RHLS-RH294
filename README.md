# RHLS-RH294
RH294 - Red Hat Enterprise Linux Automation with Ansible

---

### RHEL specific

[Create customized RHEL images for the WSL environment](https://developers.redhat.com/articles/2023/11/15/create-customized-rhel-images-wsl-environment?source=sso)

[How to Install EPEL Repository in RHEL 9 Linux](https://www.tecmint.com/install-epel-repo-rhel-9/)

[8 steps to developing an Ansible role in Linux](https://www.redhat.com/sysadmin/developing-ansible-role)
In this article, an existing Ansible playbook is used to deploy Vim and convert it to a role adding flexibility and reusability.

---

### Debian specific

#### install ansible-creator, ansible-builder, ...

```bash
# ref : https://stackoverflow.com/a/76672519
sudo    apt install python3.11-venv
python3 -m venv ~/.local --system-site-packages
 ~/.local/bin/pip install ansible-creator ansible-builder
source ~/.profile
```
