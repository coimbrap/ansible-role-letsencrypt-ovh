# Ansible Role - letsencrypt-ovh

nsible role for generating letsencrypt certificates by using DNS with OVH API

### Example
```
email: "cert@devo.re"
domains_list:
  - "devo.re"
  - "*.devo.re"
certbot_stop_services: haproxy
certbot_cmd_deploy_cert: "/bin/cat /etc/letsencrypt/live/devo.re/privkey.pem /etc/letsencrypt/live/devo.re/fullchain.pem > /etc/ssl/letsencrypt/devo.re.pem"
```

Avec credentials OVH dans un fichier séparé.

### License

GPLv3

### Author Information

Pierre Coimbra
