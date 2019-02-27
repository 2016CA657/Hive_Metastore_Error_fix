# Hive_Metastore_Error_fix

## Step 1: Vagrant up

Vagrant up with the vagrant file in this directory

## Step 2: SSH KeyGen 

Run the following two commands:

```
ssh-keygen -t rsa -P '' -f ~/.ssh/id_rsa
cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys
```
## Step 3: Install MySQL

```
sudo apt-get install mysql-server 
```

Type in root as password when prompted.

## Step 4: Configure Hadoop

Complete steps 7-10 and step 12 from this link:
https://www.edureka.co/blog/install-hadoop-single-node-hadoop-cluster 

- The files you need to change for steps 7-10 are located in **/usr/local/hadoop/etc/hadoop**
- Change to **/usr/local/hadoop/bin** to run step 12

## Step 5: Create hive-site.xml

- Change to **/usr/lib/hive/apache-hive-2.3.4-bin/conf**
- Create hive-site.xml file, copy it exactly from step 2 of the top answer here:
https://stackoverflow.com/questions/35449274/java-lang-runtimeexception-unable-to-instantiate-org-apache-hadoop-hive-ql-meta



