# devops-hw9

### Ansible tasks by roles
1. *builder*
 - Build an artifact on the One Node (*host1*)
 - Copy the artifact to the Local Machine to the dir */root*
 - Backup the new artifact on the Local Machine at the same dir
2. *webserver*
 - Copy last artifact to the Second Node (*host2*)
 - Start tomcat server on the Second Node
 - Delete the artifact on the Local Machine

#### Deploy project

```
ansible-playbook build_and_deploy.yml
```

#### Destroy project

```
ansible-playbook destroy.yml
```
