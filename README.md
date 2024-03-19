# RHLS-RH294
RH294 - Red Hat Enterprise Linux Automation with Ansible

one certification, two paths : 
 1. [Red Hat Enterprise Linux skills path](https://www.redhat.com/en/resources/enterprise-linux-skills-path-brief) → RHCE
 1. [Automation skills path for Linux administrators](https://www.redhat.com/en/resources/ansible-automation-platform-skills-path-brief) → Ansible/Automation

---

[gitignore](https://www.toptal.com/developers/gitignore/api/visualstudiocode,ansible,vim)

### RHEL specific

[Create customized RHEL images for the WSL environment](https://developers.redhat.com/articles/2023/11/15/create-customized-rhel-images-wsl-environment?source=sso)

[How to Fix “Failed to set locale, defaulting to C.UTF-8” in CentOS 8](https://www.tecmint.com/fix-failed-to-set-locale-defaulting-to-c-utf-8-in-centos/)

```sh
dnf install langpacks-en glibc-all-langpacks -y
```

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

### Resources 
https://gitlab.com/rgdacosta/classroom_env
https://gitlab.com/rgdacosta/ansible
free account : https://learning.oreilly.com/videos/red-hat-certified/ 
