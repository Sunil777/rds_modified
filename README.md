# rds_modified
Ansible playbook to Resize rds instances.

By AWSCLI we can Done as:-
aws rds modify-db-instance
	--region us-east-1
	--db-instance-identifier cc-mysql-prod-db
	--db-instance-class db.m4.xlarge
	--apply-immediately
