# Ansible_create_user

Add hosts to inventory

Change ssh_user if needed

Add to /group_vars/users
users:\
\- user_name: jhon.doe\
  user_key: ssh-rsa ABCDEFG
  
Example

./ping.sh       to check hosts  availability

./ksudo.sh      to create sudo users
