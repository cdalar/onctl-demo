# onctl-demo
onctl demo application

## List of Secrets needed for Github Action

1. SSH_PRIVATE_KEY: Private Key (ex ~/.ssh/id_rsa). Used for connecting to Virtual Machines. 
1. SSH_PUBLIC_KEY: Public Key (ex. ~/.ssh/id_rsa.pub). Will be put on VM's known_hosts file 
1. GH_TOKEN: A Github Token with pull-request write permissions
1. Credentials of your Cloud Provider. You can use the Cloud Providers defined Environment Variables. 
    1. AWS:
        *  AWS_REGION
        *  AWS_ACCESS_KEY_ID
        *  AWS_SECRET_ACCESS_KEY
    2. Hetzner
        * HCLOUD_TOKEN



