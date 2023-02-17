# feodra-setup
My ansible-playbook for configuring Fedora 37 Server edition running on MacOS X with UTM and QEMU

NOTE: The playbook is only used for the configuration of the VM not the provisioning and installation of the VM and the installation of the OS.

## How to run the playbook 

The first time you run the playbook you must run it with the `--ask-pass` and `--ask-become-pass` flags. 

```bash
ansible-playbook site.yml -i <hostname>,  --user <username> --ask-pass --ask-become-pass
```
