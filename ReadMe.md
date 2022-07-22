Aim:

- local development = prodocution environment = be able to deploy a full stack to GCP + receive requests
- boilerplate flask app that will render some HTML

experiment with:
- Terraform
- Ansible
- GCP
- Vagrant
- build Docker service
- push to dockerhub
- deploy docker image to server

```
apt install vagrant virtualbox
vagrant init # creates a template Vagrantfile
vagrant up --provider=virtualbox
# change the Virtualbox provider to install ansible dependencies (python bits)
# make it call ansible when we do a vagrant up
# setup ssh keys
```