# Curso avanzado de MySQL

Curso avanzado sobre MySQL y alta disponibilidad de servidores MySQL.

## Contenido del curso
* Replicación
 * Master - Slave
 * Master - Master
* Mysql Galera Cluster
* Cluster Control
* Percona XtraDB Cluster
* Escalado horizontal
 * ProxySQL
* Backup



## Usage


### Development time


```bash
npm start
```

Will open a dev-server on http://localhost:8080


> If changes are made on *config.json* dev server must be *restarted*.


### Bundle time

```bash
npm run build
```

Will create a build on _./dist/_.


### Deploy time

#### gitlab

There is a sample _.gitlab-ci.yaml.sample_ file to be used as a template for gitlab pipelines.

#### github

There is a npm script ready for publishing on github's pages:
```bash
npm run deploy:gh
```


