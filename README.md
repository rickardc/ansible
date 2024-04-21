# ansible
ansible


## Configure ssh keys 

### Create ssh private and public keys
ssh-keygen -t rsa -b 2048 -f ~/.ssh/{filename}

### Copy public key to remote host
ssh-copy-id username@remote_host