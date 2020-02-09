# Infrastructure

## Create VPC
#### run `ansible-playbook -v main.yml --extra-vars "@extra_vars.json"`  
*extra_vars should contains `profile`, `domain_name`, `key_name`, `email_id`*

## Teardown VPC
#### run `ansible-playbook -v teardown-vpc.yml --extra-var "@extra_vars.json"`  
*extra_vars is same as above*

## Launch Instance
#### run `ansible-playbook -v launchInstance.yml --extra-var "@extra_vars.json"`  
*make sure add key pair for your account*

## Terminate Instance
#### run `ansible-playbook -v terminate-instance.yml --extra-var "@extra_vars.json"`  
