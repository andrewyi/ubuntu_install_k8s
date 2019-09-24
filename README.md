# requests:

1. remote server run with ubuntu 18.04
2. we connect remote server as user 'ubuntu', sudo privilege must be granted and no password is required
3. always remember to specify '-b' when run this command
4. always remember to update k8s versions and other global variables in 'site.yml' file (i do not wanna extra vars file, it's easier to update site.yaml file)
5. always remember to update "hosts_${cluster_info}.ini" file



# run

ansible-playbook hosts_${cluster_info}.ini site.yaml -b

