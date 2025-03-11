# mysqld-exporter Chart for Helm

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/rafaelscone)](https://artifacthub.io/packages/search?repo=rafaelscone)

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