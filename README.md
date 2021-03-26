https://blog.stephane-robert.info/post/ansible-collections/
https://blog.octo.com/introduction-aux-ansible-content-collections/

Voir : https://github.com/freeipa/ansible-freeipa
ansible-galaxy collection install freeipa.ansible_freeipa
ansible-playbook -vvv -i environments/dev ./pb_install_freeipa.yml


ansible-galaxy install -r requirements.yml