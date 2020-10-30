## ssh-copy deployment

- Requires Ansible 1.2 or newer
- Expects CentOS/RHEL 6.x hosts

These playbooks deploy can ssh to remote machines without password, just edit the `hosts` inventory file to contain the
hostnames of the machines .

Then run the playbook, like this:

	ansible-playbook -i hosts site.yml

This is a very simple playbook and could let machines build mutual trust

### Ideas for Improvement

Here are some ideas for ways that these playbooks could be extended:

- Write a playbook to deploy an actual application into the server.
- Deploy Tomcat clustered with a load balancer in front.

We would love to see contributions and improvements, so please fork this
repository on GitHub and send us your changes via pull requests.
