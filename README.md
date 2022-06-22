# Ansible
set up new computer for dev

This should kickup everything:
```sh
curl https://raw.githubusercontent.com/ArielBenichou/ansible/main/ansible-run | sh
```
## User
Make sure you have the 'arielbenihcou' user.

You can create it with:
```sh
sudo adduser arielbenichou sudo
# enter a password & fill name
su -l arielbenichou
```

## SSH AGENT
When new computer dont forget to:
```sh
ssh-add ~/.ssh/id_ed25519
```
