### Cluster K8S

These playbooks will do:

* Install 03 Ubuntu instances EC2 (t2.micro 1 core)
* Remove swap all nodes
* Install Docker all nodes
* Install kubeadm, kubectl and kubelet all nodes
* Install Helm
* Create kubernetes cluster with 01 master and 02 workes
* Deploy appv1 and appv2 for testing

### Requirements

* ansible
* access AWS CLI
* python-pip
* boto3

You need to install Ansible in your computer and have an account into AWS and have a key pair file, that is used to connect into your AWS instances.

If you need to run it on another cloud, you need to change the playbook.

Install python-pip (Red Hat like).:
```bash
yum install python3-pip -y
```

Install ansible and boto3.:
```bash
pip install ansible
pip install boto3
```
This link helps you to install and configure AWS CLI .:

https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html


### Dependencies

