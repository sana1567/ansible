Автоматическое развертывание squid через ansible
ansible-playbook -i wer   --vault-password-file ~/.ansible_pass.txt host_proxy.yml --check