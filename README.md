# Secure-Credential-Manager

* Command Line Interface
* Input Master Password, and then allow to do CRUD operations
* Copy clipboard option

Initially execute settings.py file make database condiguration this will create will database SCM and create tables for secrets and entries.

> python settings.py make/delete/remake

Here make will create new database and if it already exist then will return message already configured, delete will remove the database while remake is reset the configurations.

In addition with creating database it will also ask user to make master password. Which will be used further for accessing and performing operation on password management application

> python scm.py


