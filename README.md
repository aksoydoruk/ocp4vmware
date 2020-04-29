# ocp4vmware

ansible-playbook -i inventory   upi.yaml -e 'install_config_file=install-config.yaml master_ips="192.168.3.181,192.168.3.182,192.168.3.183" worker_ips="192.168.3.184,192.168.3.185,192.168.3.186" bootstrap_ip="192.168.3.180" httpd_ip="192.168.3.153"  cidr_prefix="24" gateway="192.168.3.1"  dns_server="192.168.3.101" rhcos_template=rhcos-latest ' -vvv
 
 
 
