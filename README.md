** Make sure to pip install ansible, apt has an older copy **

# Instructions
* Start with Parrot OS
* Fisrt of all start burpsuite and accept its conditions, then close it
* Install Ansible (python3 -m pip install ansible)
* Clone and enter the repo (git clone)
* ansible-galaxy install -r requirements.yml
* Make sure we have a sudo token (sudo whoami)
* ansible-playbook main.yml

Install Requeriments

~~~bash
ansible-galaxy install -r requirements.yml
~~~

Execute:

~~~bash
ansible-playbook main.yml --ask-become-pass
~~~
