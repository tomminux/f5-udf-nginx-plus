# f5-udf-nginx-plus
Ansible playbook to install and manage NGINX Plus from F5

On infra-server execute:

    cat .ssh/id_rsa.pub

On nginx-controller host execute:
    
    echo "<id_rsa.pub of infra-server here" >> .ssh/authorized_keys
    sudo su -
    echo "<id_rsa.pub of infra-server here" >> .ssh/authorized_keys

 