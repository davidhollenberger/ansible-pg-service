# ansible-pg-service

This Ansible playbook will dynamically generate a pg_service file from AWS EC2 and Redshift instances.

pg_service documentation can be found here: https://www.postgresql.org/docs/current/static/libpq-pgservice.html

## Example Playbook

```
ansible-playbook pg_service.yml --extra-vars="pg_user=<username>"
```
