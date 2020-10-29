# my-apigee-utils
This repo is to test and create playbooks using Ansible. The idea is to automate the use of the Apigee Managment API with playbooks.

### How to:
1. Install Ansible in your machine (Ubuntu):
```
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo apt-add-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
```
2. Clone the repo in your local machine
3. Create the following env variables

* __APIGEE_ORGANIZATION__: "Your-apigee-organization-name"
* __APIGEE_PROXY_NAME__: "The-proxy-name-you-want-to-export"
* __APIGEE_USR__: "Email-for-apigee-login"
* __APIGEE_ACCESS_TOKEN__: "Passwrd-for-apigee-login"
* __PROXY_DIR__: "Path-to-save-the-proxy"

4. Run the you want with playbook with ansible
