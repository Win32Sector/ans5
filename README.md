# Description

Task Ansible 6

1. Edited nginx installation role:
- removed second virtualhost template;
- changed vhost name in playbook;
2. Added role certbot for installing certbot, adding letsencrypt cert and edit vhost config.
What can to do this role:
- install certbot
- generate new letsencrypt certificate
- change nginx vhost config
- renew cron job for renewing certs