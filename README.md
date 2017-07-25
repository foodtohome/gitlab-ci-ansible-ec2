# gitlab-ci-ansible-ec2

Docker image based on alpine for running ansible and EC2 dynamic inventory in
gitlab-ci.

Example:
```
ansible-playbook playbook.yml -i /usr/bin/ansible-ec2.py
```
