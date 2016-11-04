## Orion+MongoDB+NGINX Deployment

- Tested on Ansible 1.96 
- Expects CentOS/RHEL 6.x host/s

### Running playbook

Configure the inventory file with the propper hostnames. 

For now, **this playbook only support one MongoDB**.

Then run the playbook, like this:

	ansible-playbook -i inventory main.yaml

### Ideas for Improvement

Here are some ideas for ways that these playbooks could be extended:

- Setup a replicated MongoDB
- Use selinux ansible module 

We would love to see contributions and improvements, so please fork this
repository on GitHub and send us your changes via pull requests.
