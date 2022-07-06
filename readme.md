`ansible-playbook MyTask.yml -K`

```
ansible-playbook -i hosts.yaml create-user.yaml -vv
```

```
ansible-playbook -i hosts.yaml add-ssh-key.yaml -vv --extra-vars "ansible_sudo_pass=<sudo-password>"
```
