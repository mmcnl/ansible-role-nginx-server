## Example Playbook

    - hosts: all
      tasks:
        - import_role:
            name: mmcnl.nginx_server
          vars:
            ssl_certificate: /etc/letsencrypt/live/example.com/fullchain.pem
            ssl_certificate_key: /etc/letsencrypt/live/example.com/privkey.pem

## License

MIT
