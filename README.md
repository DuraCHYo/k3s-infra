1. ansible-playbook playbooks/create-user.yml -i inv/local.yml -u root -vv -e 'rsa_key_decrypt_pass=ansible_vault_password ansible_ssh_pass=root_password'
2. ansible-playbook all-in-one-install.yml -i ../inv/local.yml -u admin -vv
