# mysqld-exporter Chart for Helm

InputValues: 
```yaml
targetHosts:
  - name: db-exporter-default
    secretName: db-secret
    secretKeyDbUser: DB_USERNAME
    secretKeyDbPassword: DB_PASSWORD
    host: host.example.com:3306
```

It create a pod with this configuration and expose to prometheus