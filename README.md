<a href="https://ssenerg.com">
    <div style="margin-bottom:1em;"> 
        <img style="margin-right:-.2em;" align="left" src="https://i.postimg.cc/3wwHhJvM/logo-dh.png" title="SSENERG" width="100" height="100"/>
    </div>
    <div style="margin-bottom:-1.5em;">
        <h1 display="display:inline;">
            <font size="+4">DataHub</font>
        </h1>
    </div>
</a>

<div style="margin-left:5em;">
    <span style="vertical-align: middle;"><font size="+2">Horizontaly scaled and modular product for fetching and providing live and historical data from any Exchange containing many additional services with completely automated deployment</font></span>
</div>

---

# Product Structure
#### DataHub directory
```
  │
  ├── Manager
  │   ├── ci-cd.sh
  │   ├── manual.sh
  |   └── ...
  │
  ├── Initial 
  │   └── DynamicProvisioning
  │       ├── Ceph
  │       └── StorageClass
  │
  ├── Resources
  |   ├── Routing
  |   ├── CertManager
  |   ├── MetalLb
  |   ├── ExternalDNS
  |   ├── IngressNginx
  |   ├── MariaGalera
  |   ├── Quest
  |   ├── NatsJetstream
  |   ├── LDAP
  |   ├── Kerberos
  |   ├── Prometheus
  |   └── ELK
  │
  ├── DjangoPrivate
  │   ├── Updater
  │   ├── Producer 
  │   ├── Consumer 
  │   ├── CoreFeaturesLab 
  │   ├── CoreEngine
  |   └── PlayGround
  │
  └── DjangoPublic
      ├── MyPanel 
      ├── Provider 
      ├── BackTester 
      ├── FeaturesLab 
      ├── Executer 
      └── AI 
```

---

# Requirements
- **Kubernetes Cluster** v1.28.2
- **Initial Configs**
    - Deploy manually Initial Repository
- **Helm** v3.10.1
- **Python** v3.10.12
- **virtualenv** v20.24.7
- **BWS CLI** v0.3.1
