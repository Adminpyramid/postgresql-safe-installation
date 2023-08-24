# postgresql-safe-installation
Install postgress in Ubuntu 22.04 LTS , And configure username credentials together with REMOTE CONFIG
# Auther Admin
# date 24 Agosti 2023 06:44:25 alasiri EAT
# procedures installation needs some dependencies, clear layout, sequencial input of commands and finally fixing the missing required things all we be covered
requrements - make sure you have administactive privilages

$ sudo apt update # optional
$ sudo apt upgrade # optional ! This may be worse if your bundle package is small

# This install dependencies and postgresql

$ sudo apt-get install postgresql postgresql-contrib 

# varify if installed
$ systemctl status postgresql

# if not started start by 
$ systemctl start postgresql

Fixing The installation issues

CREDENTIALS
At start the username is "postgres"

enter in database 
$ sudo -u postgres psql

And type 
# \?   >> for help

user simple mysql to create user and assign a password of change your password by 

# create user Admin with password '0762469916.Py';
# 
