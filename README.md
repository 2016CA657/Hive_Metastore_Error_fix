# Hive_Metastore_Error_fix

## Step 1: Vagrant up

Vagrant up with the vagrant file in this directory

## Step 2: SSH KeyGen 

Run the following two commands:

```
ssh-keygen -t rsa -P '' -f ~/.ssh/id_rsa
cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys
```


