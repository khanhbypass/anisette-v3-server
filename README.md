# Khanhbypass's anisette server

A supposedly lighter alternative to [omnisette-server](https://github.com/SideStore/omnisette-server)
Also, this is a fork of [anisette-v3-server](https://github.com/Dadoum/anisette-v3-server)

Like `omnisette-server`, it supports both currently supported SideStore's protocols (anisette-v1 and 
anisette-v3) but it can also be used with AltServer-Linux.

## Connect to SideStore/AltStore/LiveContainer
1. Open SideStore/AltStore/LiveContainer
2. Go to Settings and find the anisette configuration
3. Enter anisette server link:

```bash
https://khanhbypasss-anisette-server.onrender.com/
```

se your desired host in the playbook. Tweak your parameters/ansible.cfg for the remote_user you use. Requires root.
```bash
ansible-playbook -i inventory setup-anisette-v3-ansible.yaml -k
```
